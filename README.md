# dgs-springboot-null

GraphQL queries return `null` even though their implementation is hardcoded to return a list of `Show` objects. Looks like the `ShowsDataFetcher.shows()` function is not even invoked
