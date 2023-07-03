# README

This repository contains a Rust scaffold that can be used with [Visual Studio Code Dev Containers](https://code.visualstudio.com/docs/devcontainers/containers).

## Stack

|               | Version        |
|---------------|----------------|
| Rust          | 1.70.0         |
| Postgres      | 14.1           |

## Installation

### Without Dev Containers

To install without using Dev Containers, follow these steps:

1. Install dependencies by running the command `$ cargo build`.

### With Dev Containers

#### Presiquisites

Before using Dev Containers, ensure that you have the following installed:

- [Visual Studio Code](https://code.visualstudio.com/)
- Docker
- Dev Containers extension

Please refer to the following documents for system requirements and installation instructions:

- [System requirements](https://code.visualstudio.com/docs/devcontainers/containers#_system-requirements)
- [Installation](https://code.visualstudio.com/docs/devcontainers/containers#_installation)

#### Reopen the project in Container

To open the project in a Dev Container, follow these steps:

1. Press <kbd>F1</kbd> or <kbd>Cmd + Shift + P</kbd> to open the Command Palette.
2. Type `Dev Containers` in the search bar to see the full list of commands.
3. Select `Dev Containers: Reopen in Containers` from the suggestions list.

Waiting for containers to be ready and all set.

## Running the project


To start the server, run the command `$ cargo run` in your terminal.

> Note: If you're running the project in a dev container, make sure to access the container before executing the `$ cargo run` command or open the VSCode terminal.

You can now visit http://localhost:8080/ to see the project running.

## References

- [Build Rust Apps With Dev Containers](https://betterprogramming.pub/build-rust-apps-with-dev-containers-3799b20ca683)
