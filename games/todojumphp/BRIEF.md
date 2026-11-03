# TodoJumPhp

a example of cli jumphp

## A command-line application (terminal)

This project is an **application**, not a game: commands (Symfony Console) and full-screen text screens
(symfony/tui) in the terminal. Follow `AGENTS.md` section 18 and `docs/cli.md`; example: `games/hello-cli`.
`bin/jumphp test todojumphp`, `bin/jumphp shot todojumphp` (read the screen text), `bin/jumphp export:standalone todojumphp --linux
--windows --macos` (one executable each: what the users download). It has no browser version: its page on the
playground presents it and links the executables.

---

## The JumPHP playground

This project was made on the JumPHP playground: the application's page is https://jumphp.net/todojumphp (in its "Applications").

- The application is `games/todojumphp/` (JumPHP keeps every project in `games/`). Read `AGENTS.md` (the JumPHP
  contract) first; replace the skeleton with the application described above; tests for each feature, as you
  write them; screenshots you look at.
- **Publishing**: every push to `main` is online within a minute (GitHub webhook). The MCP tool `sync_project`
  (server `jumphp`) publishes at once and returns the errors.
- **Its home page**: `games/todojumphp/site/` (AGENTS.md section 13, with the application's real screenshots) and
  `games/todojumphp/assets/thumbnail.png`.
- When it is done: MCP `update_project` with `listed: true` shows it in the playground's applications.