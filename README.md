# IPTV Orbit Player — public website and source download

This repository hosts the static Turkish/English project, privacy and support pages at its root. It also provides the complete structured application source as **[IPTV-Orbit-Player-1.2.2-source.zip](IPTV-Orbit-Player-1.2.2-source.zip)**. The root `index.html` is the project website, not the TV application runtime.

## Work on the application

Download the source ZIP and extract it. Its root directory is `iptv-orbit-player`:

```sh
unzip IPTV-Orbit-Player-1.2.2-source.zip
cd iptv-orbit-player
npm ci
npm test
npm run dev
```

Use Node.js 20.19+, 22.12+ or 24+. The local preview is http://127.0.0.1:4173. `npm run stage` prepares TV runtime resources for signing with your own Samsung certificate. The latest developer run passed 62 tests. The full application README, runtime, scripts, test fixtures, original demonstration media and license notices are inside the ZIP.

The optional **Hesapsız yerel örneği izle** path plays an original 120-second MIT local video with two synthetic AAC tone tracks and no embedded subtitles. All demo rows use this same finite file. The application does not supply provider channels or content subscriptions; use your own authorized Xtream-compatible account for real services. The app UI is Turkish.

The source ZIP is **not** a universal signed `.wgt` and does not imply Samsung store approval. No signing keys, personal provider account, device certificates, personal installation records or node_modules are included. Application MIT, original demo MIT, bundled HLS.js Apache-2.0; notices are retained.

## Privacy and support

See [Turkish privacy](privacy.html), [English privacy](privacy-en.html), [Turkish support](support.html) and [English support](support-en.html). Saved automatic-login credentials are plaintext in the TV app's localStorage. Viewing/search history and resume positions are not persisted by the app. Provider endpoints can retain their own logs.

[GitHub Issues](https://github.com/muhammetaksay/iptv-orbit-player/issues) is public. Never post credentials, PINs, personal media URLs or unredacted network logs. Publisher: Muhammet Kamil Aksay.

GitHub Pages publication and Samsung store review are separate. Hosting these files in a repository does not itself prove Pages is deployed or the TV app is available in Samsung Apps.
