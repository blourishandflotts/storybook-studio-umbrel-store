# Storybook Studio — Umbrel Community App Store

Installable preview of Storybook Studio v0.1.0.

Add this store in umbrelOS **App Store → Community App Stores**:

`https://github.com/blourishandflotts/storybook-studio-umbrel-store`

Then install **Storybook Studio**. Application image:
`ghcr.io/blourishandflotts/storybook-studio:latest` (linux/amd64).

The app is an early foundation: Library, books/chapters, media upload and playback.
It does not yet implement automated AI production.

The app's own authentication is not implemented; rely on the default Umbrel
app proxy, and do not expose the internal service directly to the internet.
Persistent data is stored under `${APP_DATA_DIR}/data`.

This store currently uses a mutable image tag while testing; pin to a verified
sha256 digest before production use.
