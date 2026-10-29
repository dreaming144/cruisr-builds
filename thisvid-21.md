# ThisVid 25 (pre-merge sideload)

Not published to `main`. Add this repository on the projector for PR 88.

- Add repository: https://raw.githubusercontent.com/dreaming144/cruisr-builds/test/thisvid-21/repo.json
- ThisVid `.cs3`: https://raw.githubusercontent.com/dreaming144/cruisr-builds/test/thisvid-21/ThisVid.cs3
- sha256: `bf0fc2d3ede25240d6d1d01bfb58f05622e1bfee963256c15a347d14ec5eb3af`
- `manifest.json` / `plugins.json` version: 25
- Source: dreaming144/cruisr `#88` branch `cursor/thisvid-https-cookie-93a2` tip `75f7ca8ed7ebabff5b2b7387650f77557d099789`
- AgeGO session cookie is sent only to thisvid.com over HTTPS. HTTP thisvid.com 301s drop the cookie. No WebView, no Google login.
