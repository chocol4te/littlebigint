# littlebigint

[![Build Status](https://travis-ci.com/chocol4te/littlebigint.svg?branch=master)](https://travis-ci.com/chocol4te/littlebigint)
[![codecov](https://codecov.io/gh/chocol4te/littlebigint/branch/master/graph/badge.svg)](https://codecov.io/gh/chocol4te/littlebigint)
[![Dependabot Status](https://api.dependabot.com/badges/status?host=github&repo=chocol4te/littlebigint)](https://dependabot.com)

Zero allocation big integer library for `no_std` Rust, borrowing heavily in terms of code and algorithms from [`num-bigint`](https://github.com/rust-num/num-bigint).

Honestly, you're probably much better off using [`num-bigint`](https://github.com/rust-num/num-bigint). Only use this library if you _absolutely_ need to be zero allocation because it just doesn't have the same breadth of functionality nor the extensive testing of [`num-bigint`](https://github.com/rust-num/num-bigint).

Quite the pep talk, I know.

## To Do

- [ ] Basic operations

  - [x] Addition
  - [x] Subtraction
  - [x] Multiplication
  - [ ] Division/Remainder
  - [ ] Power

- [ ] `fmt::Display`

- [ ] Modulo operations

- [ ] Signed operations

- [ ] Documentation
  - [ ] _Document required buffer and slice sizes_

## Contributing

Issues and PRs very welcome :)

## License

Distributed under the same license as [`num-bigint`](https://github.com/rust-num/num-bigint), Apache 2.0/MIT.
