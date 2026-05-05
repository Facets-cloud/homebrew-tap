# Facets Cloud Homebrew Tap

Single Homebrew tap for Facets Cloud's command-line tools.

## Install

```bash
brew tap Facets-cloud/tap
brew install <formula>
```

Or in one shot:

```bash
brew install Facets-cloud/tap/<formula>
```

## Available formulas

| Formula | Description | Source |
|---------|-------------|--------|
| `praxis` | Bring Praxis cloud capabilities to any local AI host | [Facets-cloud/praxis-cli](https://github.com/Facets-cloud/praxis-cli) |

(Additional Facets CLIs will land here as they're released.)

## Update

```bash
brew update && brew upgrade <formula>
```

## How this tap is maintained

Formula files in `Formula/` are written automatically by each project's
release pipeline (goreleaser pushes a formula update on every tagged
release).

## License

MIT. See [LICENSE](LICENSE).
