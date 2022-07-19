<!-- BEGIN:REMOVE_FOR_NPM -->
[![codecov](https://codecov.io/gh/libsabl/adp-rdb-js/branch/main/graph/badge.svg?token=TVL1XYSJHA)](https://app.codecov.io/gh/libsabl/adp-rdb-js/branch/main)
<!-- END:REMOVE_FOR_NPM -->

# @sabl/adp-rdb
## Adapter pattern for relational databases

**adapter** is a pattern for structuring basic create, read, update, and delete (CRUD) operations for a storage of [records]().

The adapter pattern itself is agnostic of data source type, and interfaces describing a repository are defined by authors in their own code. 

This library includes reusable mechanics for *implementing* an adapter-patterned repository that uses a relational database as its underlying storage. This library is still platform agnostic. 

Most aspects of the adapter pattern are indeed *patterns* that authors implement in their own code bases. This library provides a small collection of common building blocks for implementing the adapter pattern in TypeScript / JavaScript.

For more detail on the adapter pattern, see sabl / [patterns](https://github.com/libsabl/patterns#patterns) / [adapter](https://github.com/libsabl/patterns/blob/main/patterns/adapter.md).

<!-- BEGIN:REMOVE_FOR_NPM -->
> [**sabl**](https://github.com/libsabl/patterns) is an open-source project to identify, describe, and implement effective software patterns which solve small problems clearly, can be composed to solve big problems, and which work consistently across many programming languages.

## Developer orientation

See [SETUP.md](./docs/SETUP.md), [CONFIG.md](./docs/CONFIG.md).
<!-- END:REMOVE_FOR_NPM -->

## API
  