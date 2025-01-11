# merge-pr-action

Merge a pull request.

<!-- actdocs start -->

## Description

This action merges a specified pull request.
If [auto-merge][auto-merge] is enabled for the repository,
the pull request will be merged automatically once all required reviews are approved and all status checks pass.

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

- [merge-workflows](https://github.com/tmknom/merge-workflows): Collection of merge workflows.

## Release notes

See [GitHub Releases][releases].

[auto-merge]: https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/configuring-pull-request-merges/managing-auto-merge-for-pull-requests-in-your-repository
[releases]: https://github.com/tmknom/merge-pr-action/releases
