# test-blueprint

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] test-blueprint`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree test-blueprint`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init test-blueprint
kpt live apply test-blueprint --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
