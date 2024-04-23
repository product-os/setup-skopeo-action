# Setup Skopeo Action

This action installs [skopeo](https://github.com/containers/skopeo) in your GitHub Actions workflow.

## Usage

```yaml
uses: balena-io-experimental/setup-skopeo-action@main
with:
  # Skopeo release to install (see https://github.com/lework/skopeo-binary/releases)
  # Default: 'latest'
  version: ''

  # Skip using the tool cache and always re-download
  # Default: 'false'
  skip-cache: ''
```
