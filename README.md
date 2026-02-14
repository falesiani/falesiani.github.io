# Personal web page

Based on [Hugo Academic](https://github.com/HugoBlox/theme-academic-cv).

## Local development

The project uses **Hugo Extended 0.155.3** (see `.hugo-version` and `netlify.toml`). Theme is compatible with Hugo 0.150+.

```bash
# Install Hugo (Extended) 0.155+ e.g. via Homebrew
brew install hugo

# Install theme deps (Tailwind CSS) and fetch Hugo modules
npm ci
hugo mod get -u

# Run the site
hugo server
```

Use `hugo server -D` to include future-dated content (e.g. 2026 publications). Netlify runs `npm ci` before `hugo` automatically.