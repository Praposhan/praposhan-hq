# PRAPOSHAN HQ
Live team workspace, served by GitHub Pages at https://praposhan.github.io/praposhan-hq/
`index.html` is the whole app. Fonts sit beside it. The backend is `apps-script/HQDesk.gs` in `praposhan-platform`.
Editing `index.html`: the page has a Content-Security-Policy that pins a hash of the inline script. After any script change, update the `sha256-` value in the meta tag.
No keys, client data or passwords in this repo (it is public).
