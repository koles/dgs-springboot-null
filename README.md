# dgs-springboot-null

GraphQL queries return `null` even though their implementation is hardcoded to return a list of `Show` objects. 

It looks like the `ShowsDataFetcher.shows()` function is not even invoked:

![GraphiQL Screenshot](https://raw.githubusercontent.com/koles/dgs-springboot-null/master/demo.png)
