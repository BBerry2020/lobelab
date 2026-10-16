# three.js bundle for LobeLab

`index.html` embeds a minified, tree-shaken build of three.js containing only the classes LobeLab uses.
`entry.js` lists those classes and exposes them as `window.THREE`.

To rebuild (for example after updating the `three` version in `package.json`):

```sh
npm install
npm run build
```

Then replace the contents of the three.js `<script>` block in `index.html` with `three-lobelab.min.js`,
keep the licence comment at its top, and update the version in `THIRD-PARTY-NOTICES.md`.
If a new LobeLab feature uses another three.js class, add it to `entry.js` first.
