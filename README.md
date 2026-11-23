# Adnan Mawass — Developer portfolio

A responsive static portfolio featuring Shopos, Tap and Go, and Premier League Predictions. Its orbital visual theme is an original design inspired by the section layout of [Mahmoud Hachem’s portfolio](https://mahmoudhachem.dev).

Open `index.html` in a browser or serve the repository root with `python3 -m http.server 8000`. The repository root can be hosted with GitHub Pages. There is no build step.

Skill marks are from [Simple Icons](https://simpleicons.org/) and the [OpenNext documentation](https://opennext.js.org/). The Simple Icons license and disclaimer are in `assets/skills/`. Brand marks identify their respective technologies. See [LICENSE](LICENSE) for the original Simplefolio license retained from the first version.

## Cloudflare Workers

For the existing `portfolio` Worker, connect this repository under **Settings → Builds**. Use production branch `main` and the repository root. Leave **Build command** empty and use `npx wrangler deploy` as the **Deploy command**. Wrangler runs the static build in `wrangler.jsonc` and uploads `dist/`.

To test the deployment package without publishing, run `npx wrangler deploy --dry-run`.
