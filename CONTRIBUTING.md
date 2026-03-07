# Contributing to Dark-Web

Thank you for your interest in contributing! This repository is a curated list of Dark Web tools and resources. Contributions that add new tools, fix broken links, or improve existing descriptions are very welcome.

## How to Contribute

### 1. Fork & Clone

1. Fork this repository by clicking the **Fork** button at the top of the page.
2. Clone your fork locally:
   ```bash
   git clone https://github.com/<your-username>/Dark-Web.git
   cd Dark-Web
   ```

### 2. Create a Branch

Always work on a dedicated branch — never commit directly to `main`:

```bash
git checkout -b add-<tool-name>
```

### 3. Make Your Changes

Edit `README.md` to add or update content. Please follow the existing formatting conventions:

- Place the new entry in the **correct section** (Search Engines, Crawlers, Scanners, etc.).
- Use the established bullet-point format:
  ```markdown
  * Tool Name - [https://github.com/owner/repo](https://github.com/owner/repo)
  ```
- If a tool has multiple links (e.g. a clearnet URL and an `.onion` URL), list them on the same line separated by a comma.
- Keep links alphabetically ordered within each section where possible.
- Use **HTTPS** links wherever the site supports it.

### 4. Adding a New Tool

Before submitting a new tool, please make sure it meets the following criteria:

- **Relevant** — the tool is directly related to Dark Web research, security, or OSINT.
- **Accessible** — the GitHub repository or website is publicly available.
- **Active** — the project is not abandoned (has had at least one commit or update in the last two years), or is historically significant.
- **Legal** — the tool is intended for legitimate security research or educational purposes.

### 5. Commit and Push

Write a clear, concise commit message:

```bash
git add README.md
git commit -m "Add <Tool Name> to <Section Name>"
git push origin add-<tool-name>
```

### 6. Open a Pull Request

Open a Pull Request from your branch to the `main` branch of this repository. In the PR description please include:

- **Tool name** and a one-line description of what it does.
- **Link** to the tool's repository or website.
- **Why** it belongs in this list.

## Reporting Issues

If you find a broken link, an outdated entry, or anything else that needs attention, please [open an issue](https://github.com/mwakidenis/Dark-Web/issues) and describe the problem.

## Code of Conduct

Be respectful and considerate in all interactions. Contributions that promote illegal activity or harm will not be accepted.
