#Solved with Flexbox

##Building navigation bar

```
@media (min-width: 800px) {

	.main-header,
	.main-nav {
		display: flex;
	}
	.main-header {
		flex-direction: column;
		align-items: center;
	}
}

@media (min-width: 1050px) {

	.main-header {
		flex-direction: row;
		justify-content: space-between;
	}
}

```