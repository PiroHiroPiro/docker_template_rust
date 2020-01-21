# Rust Docker template

This is a Docker template that provides an environment with Rust.

## Requirement

- [Docker](https://www.docker.com/)
  - docker-compose

## Usage

Run rust:

```console
$ docker-compose run rust bash
# rustc main.rs
# ./main
# cargo run
```

## Install

Clone repository:

```console
$ git clone https://github.com/PiroHiroPiro/docker_template_rust.git
$ cd docker_template_rust
```

Build images:

```console
$ docker-compose build
```

Initialize Cargo:

```console
$ docker-compose run rust cargo init
```

## Licence

This software is released under the MIT License, see [LICENSE](https://github.com/PiroHiroPiro/docker_template_rust/blob/master/LICENSE).

## Author

[Hiroyuki Nishizawa](https://github.com/PiroHiroPiro)
