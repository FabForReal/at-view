# at-view

a lightweight unauthenticated public bluesky viewer running on the client.
it only shows the most recent activity of the user.
users with a "!no-unauthenticated" label will be hidden.

built using astro 7 on cloudflare workers, uses @atcute packages for atproto stuff.

why? idk.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |