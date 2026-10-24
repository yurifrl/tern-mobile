# tern-mobile

omp plugin: bridges this omp session (prompt draft, model, busy state) to the
[tern-awui](https://github.com/materemias/tern-awui) server, and applies drafts and model picks
typed on the phone.

Vendored from `materemias/tern-awui` `omp-extension/tern-mobile.ts` at commit `759a551`
(MIT); packaged as an omp plugin so it installs with `omp plugin link <checkout>` instead of a
raw symlink into `~/.omp/agent/extensions/`. The bridge reads the server's `bridge.json` from
`~/.config/tern-mobile/`; the server itself is installed and run by tern-awui's own installer.
