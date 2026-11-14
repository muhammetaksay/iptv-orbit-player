# IPTV Orbit Player — public website and source download

This repository hosts the static project, privacy and support pages at its root. The complete structured application source is **[IPTV-Orbit-Player-1.2.3-source.zip](IPTV-Orbit-Player-1.2.3-source.zip)**. Root `index.html` is the website, not the TV application runtime. The earlier 1.2.2 source archive remains a separate immutable version.

## Run the application source

Download and extract the archive, whose root is `iptv-orbit-player`:

```sh
unzip IPTV-Orbit-Player-1.2.3-source.zip
cd iptv-orbit-player
npm ci
npm test
npm run dev
```

Use Node.js 20.19+, 22.12+ or 24+. The local preview is http://127.0.0.1:4173. `npm run stage` prepares runtime resources for signing with your own Samsung certificates. The latest developer run passed **65 tests**. The full application README, source-code text export, runtime, scripts, synthetic test fixtures, original demo and license notices are inside the ZIP.

The optional **Hesapsız yerel örneği izle** path plays an original MIT-licensed 120-second local video with two synthetic AAC tone tracks and no embedded subtitles. Every demo row opens that same finite file. The player supplies no provider channels or content subscriptions; connect your own authorized Xtream-compatible service for real media. The app interface is Turkish.

Version 1.2.3 adds **Bilgi ve gizlilik** on login and home/browser screens. Its local information overlay works without an account, PIN or network and describes plaintext auto-login storage, direct provider connections, separate settings/PIN retention and support. Return from full-screen video to see the header control.

The source ZIP is **not** a universal signed `.wgt` or Samsung store approval. No signing keys, personal provider credentials, device certificates, personal installation records or node_modules are included. Application MIT, original demo MIT, bundled HLS.js Apache-2.0; notices retained.

## Privacy and support

Privacy: [Türkçe](privacy.html), [English](privacy-en.html), [한국어](privacy-ko.html). Support: [Türkçe](support.html), [English](support-en.html).

Publisher: **Muhammet Kamil Aksay**. Authorized public privacy/support contact: **aksay84@gmail.com**, **+90 505 014 95 55**. [GitHub Issues](https://github.com/muhammetaksay/iptv-orbit-player/issues) is also available and public. Never send credentials, PINs, personal media URLs or unredacted network logs.

Saved login credentials are plaintext in the TV app's localStorage. Viewing/search history and resume positions are not persisted. Account reset removes saved login but leaves independent preferences/PIN settings. Data-removal behavior depends on the TV; no uninstall guarantee is made. Provider/media hosts may retain their own logs.

Website publication and Samsung store review are separate. A repository or website does not itself prove the TV app is approved or available in Samsung Apps.
