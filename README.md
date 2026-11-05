# Federary Network

A federation administration console for inspecting trusted instances, federation links, moderation queues and decentralized identity handshakes.

An ACRYL Blends blueprint for the **Decentralized** category (`acrylblends.decentralized-federary`, category 73 of 100).

Status: designed, being built. `design/spec.md` is the specification and `design/mockup.html` the mockup (open it in a browser). The app itself,
composed from Cordis plugins (one `plugins/<feature>/` folder and one `blend.yaml` row per feature), lands here when it passes review.

When it is ready you will start it with:

```sh
npm create acrylblends@latest my-app -- --from acrylblends.decentralized-federary
cd my-app && npm install && npm run dev
```

Listed on https://acrylblends.github.io/blends and https://acryl.dev/blends.
