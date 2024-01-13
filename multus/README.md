# multus

## Description
multus description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] multus`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree multus`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init multus
kpt live apply multus --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
