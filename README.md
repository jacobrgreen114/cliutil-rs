# cliutil
[![Rust](https://github.com/jacobrgreen114/cliutil-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/jacobrgreen114/cliutil-rs/actions/workflows/rust.yml)

Cliutil is planned to be a collection of utilities for command line interfaces.

Changes can be found in the [changelog](CHANGELOG.md).

## Current State
'cliutil' is currently very alpha.  It is not recommended for use in production code.

#### Apis
- 'cliutil::constexpr' - Api for creating a compile-time static command line application.

#### Todos
- 'cliutil::constexpr'
    - implement help / version subcommands
    - implement proper error reporting
    - implement command, flag, and parameter name duplication checks

## Future Plans
#### Apis
- 'cliutil::runtime' - creates a cli app config at runtime. This will be useful for creating very dynamic cli apps.
