# authorization-test

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] authorization-test`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree authorization-test`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init authorization-test
kpt live apply authorization-test --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
