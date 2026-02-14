# Personal web page

Based on [Hugo Academic](https://github.com/HugoBlox/theme-academic-cv).

## Local development

Use **Hugo 0.126.3** to match Netlify and avoid theme compatibility issues:

```bash
# If using Homebrew
brew install hugo@0.126
hugo server  # use the 0.126 binary, or: /opt/homebrew/opt/hugo@0.126/bin/hugo server

# Or install exact version: https://github.com/gohugoio/hugo/releases/tag/v0.126.3
```

Then run `hugo server` (or `hugo server -D` to include future-dated content).