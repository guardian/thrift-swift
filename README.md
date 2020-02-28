thrift-swift
============

This repository exists so that the Thrift Swift library can be used with Swift Package Manager.  SPM requires that packages have a Package.swift file at the repository root, which is not possible with the multi-language structure of the main thrift repository.

The library readme is available [here](https://github.com/apache/thrift/blob/master/lib/swift/README.md)

## Versioning

The git submodule currently points to a [Guardian fork](https://github.com/guardian/french-thrift) of Apache Thrift. This is a few commits ahead of Apache's repo. To use Swift Package Manager we need to tag each update to the git submodule, so we've tagged them with `0.14.0-gu{n}`. We started at `0.14.0-gu2` and each subsequent version should have an increasing suffix. The thinking behind this is that when Apache confirm their next release it will most likely be `0.14.0`.
