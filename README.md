# merge-pr-action

Merge a pull request.

<!-- actdocs start -->

## Description

This action merges a specified pull request.

## Usage

```yaml
  steps:
    - name: Merge PR
      uses: tmknom/merge-pr-action@v0
      with:
        pull-request: 10
```

## Inputs

| Name | Description | Default | Required |
| :--- | :---------- | :------ | :------: |
| pull-request | Specifies the pull request to merge as a `number`, `url`, or `branch`. | n/a | yes |

## Outputs

| Name | Description |
| :--- | :---------- |
| auto-merge | Indicates whether the auto-merge setting is enabled for the repository. |

<!-- actdocs end -->

## Permissions

| Scope         | Access |
| :------------ | :----- |
| contents      | write  |
| pull-requests | write  |

## FAQ

N/A

## Related projects

N/A

## Release notes

See [GitHub Releases][releases].

[releases]: https://github.com/tmknom/merge-pr-action/releases
