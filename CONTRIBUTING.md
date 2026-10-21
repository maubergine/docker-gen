# Contributing

docker-gen renders templates from Docker container metadata (a fork of jwilder/docker-gen).

Bug reports and feature requests are welcome as [issues](https://github.com/maubergine/docker-gen/issues). Pull requests are
welcome too; CI on a pull request from a fork may wait for the maintainer to approve it.

## Commits

Use [Conventional Commits](https://www.conventionalcommits.org/): `fix:`, `feat:`, `chore:`, `docs:` and so on. This
fork doesn't cut releases, so the type only describes the change. CI checks every commit (`commitlint.yml`). To check them locally before you push:

```sh
npm install   # installs commitlint and turns on .githooks/commit-msg
```

Commits to `master` must be signed.

## Tests

```sh
go build ./...
go test -vet=off ./...
```
