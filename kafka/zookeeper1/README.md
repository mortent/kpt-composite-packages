# zookeeper1

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] zookeeper1`
Details: https://googlecontainertools.github.io/kpt/reference/pkg/get/

### View package content
`kpt pkg tree zookeeper1`
Details: https://googlecontainertools.github.io/kpt/reference/pkg/tree/

### Apply the package
```
kpt live init zookeeper1
kpt live apply zookeeper1 --reconcile-timeout=2m --output=table
```
Details: https://googlecontainertools.github.io/kpt/reference/live/
