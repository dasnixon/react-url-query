# Change log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

# 1.1.0

- Adds in support for changing multiple query parameters at once through the `onChangeUrlQueryParams()` callback. This function is passed as a prop when `addChangeHandlers` is true. It takes an object that maps prop names to unencoded values and updates all of them at once. See the [Basic Example](https://github.com/pbeshai/react-url-query/blob/master/examples/basic/src/MainPage.js).
- You can also make use of new helper functions `multiReplaceInUrlQuery()` and `multiPushInUrlQuery()`.

