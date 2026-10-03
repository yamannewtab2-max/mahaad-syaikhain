# Mahaad Syaikhain — homepage

One page, no build step. `index.html` holds everything:

- **Home** — name + two buttons: *Sign my kid*, *View my kids progress*
- **Sign my kid** — kid name, parent phone, class → saved on the device (localStorage, key `ms.kids.v1`)
- **Progress** — list of signed kids with a progress bar; tap a bar to add 10%

Data lives in the browser only (no server). Deployed on Vercel.
