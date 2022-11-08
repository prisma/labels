# labels
Only used for labels, which we copy to new repositories.

## How to use


## Prerequisites

- Install GitHub CLI: https://github.com/cli/cli#installation
- Run `gh auth login`

## First, check the labels on the destination repository

When a repository is created it comes with default labels.
Go to https://github.com/prisma/my-destination-repo/labels and delete labels before copying the new ones.

## Second, copy the labels to the destination repository

Using the command below, it will copy the [existing labels of this repository](https://github.com/prisma/labels/labels) to the repository defined, here `prisma/my-destination-repo` as an example.

```
gh label clone prisma/labels --repo prisma/my-destination-repo
! Cloned 35 labels of 44 from prisma/prisma-labels to prisma/my-destination-repo
```

See https://cli.github.com/manual/gh_label_clone documentation for more information.
