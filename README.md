# Do not use.

This is a testing repository for my own containerized builds of https://github.com/spacebarchat project.

Once ready, this will be updated with instructions. For now, everything put here is boilerplate configuration and is subject to change.

## What I wanna try to make work before I "complete" it

- Podman Quadlet setup for rootless and rootful deployment alike
- A configuration that works with Caddy
- Easy production-ready setup that integrates basics (Postgres + Spacebar Server + Fermi)
- More advanced use-cases (Postgres + Spacebar Server + RabbitMQ + Imagor + Fermi)
- Friendly documentation for this specific image

insert something else here once it comes to my mind. I've tried making one with `scratch` image but that feat is *very* costly in terms of compute as compiling nodejs statically and having it work afterwards is an insane timesink.

---

## 🦆 Rubberverse Container Images

![Image Tag](https://img.shields.io/github/v/tag/Rubberverse/spacebar-server) ![License](https://img.shields.io/github/license/Rubberverse/spacebar-server)

Not sure what to pull? Check currently available [images](https://github.com/Rubberverse/qor-caddy/pkgs/container/qor-caddy).

## Features

- Debian builder and runner
- Runs as `spacebar` user with UID and GID values of `1001:1001`
- No `s6-overlay`, `gosu` or other rootful container init

## Runner env variables

//TODO

## Build-time env variables

//TODO

## Manually building

//TODO
