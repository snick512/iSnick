[iSnick.net](https://isnick.net), a simple web portal showcasing open source projects by [snick512](https://github.com/snick512).

### Features

- **Pinned Projects:** Displays a curated list of open source projects.
- **Project Details:** View project description, language, stars, forks, last updated date, latest 10 commits, and the README.
- **Live GitHub Data:** Fetches project info, commit history, and README directly from the GitHub API.
- **Responsive UI:** Built with [Tailwind CSS](https://tailwindcss.com/) for a modern, dark-themed interface.
- **No Build Tools:** All logic is in a single HTML file with embedded JavaScript.

### How it Works

- The homepage lists pinned repositories.
- Clicking "Details" on a project shows its details, commit history, and README.
- All data is fetched live from GitHub using the public API.
- Markdown rendering is handled by a lightweight inlined parser (`LiteMD`) or GitHub's HTML API.

### Usage

Just open [`index.html`](index.html) in your browser, or deploy it to any static web host.

### Support

If you find this useful, consider supporting via [Liberapay](https://go.tyclifford.com/liberapay) or [tip](https://tyclifford.com/tip).

---

iSnick — Built with ❤️ in Open Source, West Virginia