# o5gs-cp-helm-release

## Description
o5gs-cp-helm-release description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] o5gs-cp-helm-release`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree o5gs-cp-helm-release`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init o5gs-cp-helm-release
kpt live apply o5gs-cp-helm-release --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
