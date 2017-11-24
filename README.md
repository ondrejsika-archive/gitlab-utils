# gitlab-utils

    Ondrej Sika <ondrej@ondrejsika.com>
    https://github.com/ondrejsika/deb-utils

Utils for Gitlab and Gitlab CI

## Install

```
git clone git@github.com:ondrejsika/gitlab-utils.git
```

## Activate

```
export PATH=$PATH:`pwd`/gitlab-utils
```

## Scripts

### gu-setup-ci-runner

Create and setup Docker container with Gitlab CI Runner

```
gu-setup-ci-runner <gitlab url> <token> <runner name>
```

Example

```
gu-setup-ci-runner https://gitlab.com a0a0a0a0a0 sika-x1

```

