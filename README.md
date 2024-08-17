# nginx-app

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nginx-app`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nginx-app`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nginx-app
kpt live apply nginx-app --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
