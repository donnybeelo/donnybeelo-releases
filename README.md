# Daniel Elia's Flatpaks

Flatpak repository served at https://releases.donnybeelo.net.

## Branches

- `main`: the build workflow (`.github/workflows/release.yml`).
- `pages`: the published ostree repo and site, written by the workflow and served by GitHub Pages.

## Install

```
flatpak remote-add --if-not-exists donnybeelo https://releases.donnybeelo.net/donnybeelo.flatpakrepo
```
