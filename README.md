# baseimage

[![CircleCI](https://circleci.com/gh/dentalcpdpro/baseimage.svg?style=svg&circle-token=6855cedeb632a21dfc2a97b46b9d96240c6c8b12)](https://circleci.com/gh/dentalcpdpro/baseimage)

Base docker images both for building and running app.

- `ARG UPGRADE` in `Dockerfile.*` must be located above all other `ARG
  UPGRADE_*`, if any.
