<p align="center">
  <img src="./keeply-logo.png" width="90" alt="Keeply" />
</p>

<h2 align="center">Keeply</h2>

<p align="center">A personal bookmark manager that stays out of your way.</p>

<p align="center">
  <a href="https://keeply.tools">keeply.tools</a>
  &nbsp;·&nbsp;
  <a href="https://app.keeply.tools">Sign in</a>
  &nbsp;·&nbsp;
  <a href="https://dev.keeply.tools">Docs</a>
</p>

---

Keeply is a bookmark manager for people who actually use their bookmarks. Save URLs from the browser or the command line, organize with folders and tags, and search across everything when you need something back.

There's also a CLI if you'd rather not leave the terminal.

### Install the CLI

```bash
# Homebrew
brew tap keeply-link/keeply
brew install keeply

# or via npm
npm install -g @keeply-link/cli
```

Once installed:

```bash
keeply login
keeply add https://example.com --tag reading
keeply list --tag reading
keeply search "topic you saved last week"
```

Full CLI reference at [dev.keeply.tools](https://dev.keeply.tools).

### Repos

| Repo | Description |
| --- | --- |
| [`keeply-cli`](https://github.com/keeply-link/keeply-cli) | The CLI tool, MIT licensed |
| [`homebrew-keeply`](https://github.com/keeply-link/homebrew-keeply) | Homebrew tap for macOS and Linux installs |
