## Examples

    $ jets release:history
    Releases for stack: demo-dev
    +---------+-----------------+--------------+---------+
    | Version |     Status      | Released At  | Message |
    +---------+-----------------+--------------+---------+
    | 3       | UPDATE_COMPLETE | 10 hours ago | Deploy  |
    | 2       | UPDATE_COMPLETE | 18 hours ago | Deploy  |
    | 1       | UPDATE_COMPLETE | 22 hours ago | Deploy  |
    +---------+-----------------+--------------+---------+

The shown releases are paginated. If you need to see more releases you can use the `--page` option.

    $ jets release:history --page 2

## Other Commands

  release:info      View detailed information for a release
