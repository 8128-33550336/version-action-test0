<samp>
<div align="center">

# version-action-test0

[日本語](./README.md)

</div>

In this repository, creating a Pull Request (PR) from branches like `develop` to `main` and merging it will trigger GitHub Actions.

## Version Management

This project adopts **Semantic Versioning**.
If your PR title includes any of the following keywords, a corresponding version update will be performed:

* `[major]`: Major update
* `[patch]`: Patch update
* `[minor]`: Minor update
* **If no keyword is included**: Minor update

A new version tag will be created, and a release will be published.

Please note that the "Install dependencies" and "build" steps are implemented as mocks.

</samp>
