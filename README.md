# GOSIM Spotlight Hangzhou 2025

## How to add FAQ
1. Add data to JSON file at `src/json/FAQ.json`

## How to edit Markdown pages (Code of Conduct, Privacy, Workshop)
1. Edit the Markdown file at `src/markdown/`

## Header Notification bar
1. By default we have the notification bar active. If you want to remove the notification bar, go to Header.astro and change "const hasNotificationBar = true;" to false.

## 🚀 Project Structure

```text
/
├── public/
│   └── fonts
│   └── icons
│   └── images
│       └── speakers
│       └── sponsors
│   └── js
│   └── videos
├── src/
│   ├── layouts/
│   ├── components/
│   └── pages/
│   └── styles/
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [guide on project structure](https://docs.astro.build/en/basics/project-structure/).

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

## Want to learn more?

Feel free to check [the Astro documentation](https://docs.astro.build).
