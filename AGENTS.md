## Cursor Cloud specific instructions

This repository is a **GitHub Profile README** consisting of a single `README.md` file (HTML inside Markdown). There are no application services, build steps, dependencies, tests, or lint configurations.

### Previewing

To preview the rendered README locally, use [grip](https://github.com/joeyespo/grip):

```
pip install grip
grip README.md 6419
```

Then open `http://localhost:6419` in a browser.

### Notes

- The `README.md` references external badge/widget services (GitHub Readme Stats on Vercel, GitHub Streak Stats on Heroku). These are third-party and not controlled by this repo.
- There are no automated tests, linters, or build commands to run.
- Changes are validated visually by rendering the Markdown/HTML.
