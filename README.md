# NyxOrbit legal

The Terms of Service and Privacy Policy for NyxOrbit, its launcher and its game
server. Three plain HTML pages, each with its own styles inline: no scripts, no
fonts or files from anywhere else, no build step.

- `index.html` links both
- `terms.html`
- `privacy.html`

The launcher (0.2.2 on) opens them from Settings, About at:

- https://notx2cc.github.io/nyxorbit-legal/terms.html
- https://notx2cc.github.io/nyxorbit-legal/privacy.html

So they go up with GitHub Pages from a public repo named `nyxorbit-legal` under
`notx2cc`, served from the root of its default branch. Edit, commit, push;
Pages redeploys on its own.

The privacy page is written from what the code does: the launcher
(`src/main.mjs`), the game server (`Tools/SimServer`, `Accounts.cs`,
`Saves.cs`, `Program.cs`) and the game's chat and presence code. If any of them
starts keeping or sending something new, this page is part of that change, and
its date moves with it.

The older pages in `voltium-legal` also covered the two Discord bots. The
Discord section here carries over what they said about the bot's pilot count
and the tickets.
