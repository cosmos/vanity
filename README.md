# Vanity URL

Cosmos-sdk [Vanity URL](https://gianarb.it/blog/go-mod-vanity-url) for go mods.
We use [vangen](https://github.com/leighmcculloch/vangen) for generating this repo.

## How to add a module

- `go install 4d63.com/vangen@latest`
- Add a new entry in `vangen.json`
- `vangen -config vangen.json -out .`
- Push your changes
