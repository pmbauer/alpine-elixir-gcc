Elixir on Alpine Linux + GCC
=====

Elixir minimal environment for compiling Elixir applications with NIFs.

Latest version: **1.2.1**  
Image size: **147.5 MB**  
Parent: [pmbauer/elixir-dev](https://github.com/pmbauer/alpine-erlang)

This is based on work for `msaraiva/erlang` but includes an init system for PID 1 and DNS fixes for Alpine's lack of support for `search` in `resolv.conf`.

https://github.com/janeczku/docker-alpine-kubernetes


See [Erlang/Elixir on Alpine Linux](https://github.com/msaraiva/alpine-erlang) to learn more about creating **minimal Erlang/Elixir docker images with Alpine Linux**.

The following packages are pre-installed:

- All packages from [pmbauer/elixir-dev](https://registry.hub.docker.com/u/pmbauer/elixir-dev/)
- binutils-libs
- binutils
- libgomp
- pkgconf
- pkgconfig
- gmp5
- mpfr3
- mpc1
- gcc
- make
- musl-dbg
- musl-dev
- linux-headers
- libc-dev
- libgcc

