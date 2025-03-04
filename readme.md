# Taskfile Collection

This repository contains various task definitions for [Task](https://taskfile.dev/), a task runner / build tool that aims to be simpler and easier to use than GNU Make.

## Available Tasks

- [golang-migrate](./golang-migrate/README.md) - Tasks for database migrations using [golang-migrate](https://github.com/golang-migrate/migrate)

## Usage

See the [Task documentation](https://taskfile.dev/usage/) for general usage instructions.

To use a specific task collection, navigate to its directory and run the appropriate task command.


## How to include

```yaml
version: 3

includes:
  migrate: https://raw.githubusercontent.com/digged-org/gist/refs/heads/main/golang-migrate-task/task.yaml
```