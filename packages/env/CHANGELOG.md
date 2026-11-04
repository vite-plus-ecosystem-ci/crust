# @crustjs/env

## 0.1.2

### Patch Changes

- [#510](https://github.com/chenxin-yan/crust/pull/510) [`6fdb8a6`](https://github.com/chenxin-yan/crust/commit/6fdb8a642b79a176d60d9a3d4be3431493201052) Thanks [@chenxin-yan](https://github.com/chenxin-yan)! - `tryCoerceNumber` returns `undefined` for empty or whitespace-only input instead of `0`. Store `type: "number"` fields reject a persisted blank string with a `VALIDATION` error instead of reading it as `0`, and `@crustjs/env` reports `PORT=""` as invalid for `type: "number"`, as documented.

- [#539](https://github.com/chenxin-yan/crust/pull/539) [`ce12aed`](https://github.com/chenxin-yan/crust/commit/ce12aed7a34275c49b54340d1995378afedfa2a6) Thanks [@chenxin-yan](https://github.com/chenxin-yan)! - Remove the `engines.deno` declaration; Deno is no longer supported.
- Updated dependencies [[`a805be3`](https://github.com/chenxin-yan/crust/commit/a805be3923e60e64e34fb3ac49a41b9f4b7cf71a), [`cc3048c`](https://github.com/chenxin-yan/crust/commit/cc3048cb281e4f6cf556e81ed7358d7e2fb0e52c), [`6e4e59b`](https://github.com/chenxin-yan/crust/commit/6e4e59bfa71d72daf39ceebc752e27d29b0449af), [`09a6808`](https://github.com/chenxin-yan/crust/commit/09a68080e8809b507dbcd0c581bd9942b186f44b), [`02993c7`](https://github.com/chenxin-yan/crust/commit/02993c71a43cafa1cbbd9853bf00e991efccb1cb), [`34df0c6`](https://github.com/chenxin-yan/crust/commit/34df0c604910ceab083a7e88910cc510da4a5c5a), [`6fdb8a6`](https://github.com/chenxin-yan/crust/commit/6fdb8a642b79a176d60d9a3d4be3431493201052), [`27f5832`](https://github.com/chenxin-yan/crust/commit/27f583260be2ad90544dd85d5653f7ab23255cff), [`ce12aed`](https://github.com/chenxin-yan/crust/commit/ce12aed7a34275c49b54340d1995378afedfa2a6), [`71cd6dd`](https://github.com/chenxin-yan/crust/commit/71cd6dd8b0e5af788e11ccd68616b3c7b1c693ba)]:
  - @crustjs/core@0.6.0

## 0.1.1

### Patch Changes

- [#469](https://github.com/chenxin-yan/crust/pull/469) [`1984299`](https://github.com/chenxin-yan/crust/commit/1984299962d29641ed1b9741f1ed252a1b3f8e1b) Thanks [@chenxin-yan](https://github.com/chenxin-yan)! - Raise the minimum supported Node.js version to 24. Remove the Node 22 disposal-stack fallback and use native AsyncDisposableStack on all supported runtimes. Update generated Node projects to require Node 24 and use @types/node 24.

## 0.1.0

### Minor Changes

- [#454](https://github.com/chenxin-yan/crust/pull/454) [`0b835c2`](https://github.com/chenxin-yan/crust/commit/0b835c20b9bcf09e9dea7f179eeecd43a9c50763) Thanks [@chenxin-yan](https://github.com/chenxin-yan)! - Add typed environment Contexts with redacted validation errors and command-scoped help/man sections. Reuse the core flag value pipeline and preserve ENV errors in the Effect adapter.

### Patch Changes

- Updated dependencies [[`bc3cbb2`](https://github.com/chenxin-yan/crust/commit/bc3cbb250974fcdba4ce2f50ee4b6b90a1f16c30), [`c4f44d6`](https://github.com/chenxin-yan/crust/commit/c4f44d6f9e3dd206154d0b18a84fb75464dc2dfe), [`0b835c2`](https://github.com/chenxin-yan/crust/commit/0b835c20b9bcf09e9dea7f179eeecd43a9c50763), [`eb9928d`](https://github.com/chenxin-yan/crust/commit/eb9928d60edc3033652ad55a3a019e790dafdf06), [`4977f33`](https://github.com/chenxin-yan/crust/commit/4977f33e87a928d968202af40f9729e390b7df93)]:
  - @crustjs/core@0.5.0
