# test-package-1

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] test-package-1`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree test-package-1`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init test-package-1
kpt live apply test-package-1 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
