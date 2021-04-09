# zookeeper2

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] zookeeper2`
Details: https://googlecontainertools.github.io/kpt/reference/pkg/get/

### View package content
`kpt pkg tree zookeeper2`
Details: https://googlecontainertools.github.io/kpt/reference/pkg/tree/

### Apply the package
```
kpt live init zookeeper2
kpt live apply zookeeper2 --reconcile-timeout=2m --output=table
```
Details: https://googlecontainertools.github.io/kpt/reference/live/
