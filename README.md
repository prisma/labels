# labels
Only used for labels, which we copy to new repositories.

## How to use


## Prerequisites

- Install GitHub CLI: https://github.com/cli/cli#installation
- Run `gh auth login`

## Copying the labels to another repository

Using the command below, it will copy the existing labels of this repository to the repository defined, here `prisma/my-destination-repo` as an example.

```
gh label clone prisma/labels --repo prisma/my-destination-repo
! Cloned 35 labels of 44 from prisma/prisma-labels to prisma/my-destination-repo
```
