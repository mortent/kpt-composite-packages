# kafka

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] kafka`
Details: https://googlecontainertools.github.io/kpt/reference/pkg/get/

### View package content
`kpt pkg tree kafka`
Details: https://googlecontainertools.github.io/kpt/reference/pkg/tree/

### Apply the package
```
kpt live init kafka
kpt live apply kafka --reconcile-timeout=2m --output=table
```
Details: https://googlecontainertools.github.io/kpt/reference/live/
