<p align="center">
  <img src="./keeply-logo.png" width="90" alt="Keeply" />
</p>

<h2 align="center">Keeply</h2>

<p align="center">A bookmark manager built for people who live in the terminal.</p>

<p align="center">
  <a href="https://keeply.tools">keeply.tools</a>
  &nbsp;·&nbsp;
  <a href="https://app.keeply.tools">Sign in</a>
  &nbsp;·&nbsp;
  <a href="https://dev.keeply.tools">Docs</a>
</p>

---

Keeply is a bookmark manager with a proper API, a CLI, and no browser required. Save links from anywhere, tag and organize them, and pipe them into whatever you're building. There's a web UI too if you want it.

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
