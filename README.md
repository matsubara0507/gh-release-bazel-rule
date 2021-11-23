# gh-release-bazel-rule

This is gh-extension that create GitHub release for bazel rules repository and generate `WORKSPACE` code.

## Example

```
$ gh release-bazel-rule v0.0
Successfully created release: https://github.com/matsubara0507/gh-release-bazel-rule/releases/tag/v0.0
Successfully uploaded 1 asset to v0.0
Generate WORKSPACE code:
http_archive(
    name = "gh-release-bazel-rule",
    sha256 = "93786a67e1d8a6d5f8c231a59805802c2642b08b741dbbd9b4a8c236d0fc3469",
    urls = ["https://github.com/matsubara0507/gh-release-bazel-rule/releases/download/v0.0/gh-release-bazel-rule-v0.0.zip"],
)
```
