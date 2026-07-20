# Waariss Homebrew Tap

Homebrew formulas for command-line tools maintained by Waris Damkham.

## Install jailbreakit

Install directly:

```bash
brew install waariss/tap/jailbreakit
```

Or tap the repository first:

```bash
brew tap waariss/tap
brew install jailbreakit
```

## Available formulas

| Formula | Description |
|---|---|
| `jailbreakit` | iOS pentest lab setup helper for authorized security testing |
| `whitebox-secure-scan` | Offline white-box secure-code triage for penetration testers |

Install the white-box scanner independently with:

```bash
brew install waariss/tap/whitebox-secure-scan
whitebox-secure-scan version
whitebox-secure-scan doctor
```

## Upgrade

```bash
brew update
brew upgrade jailbreakit
brew upgrade whitebox-secure-scan
```

## Uninstall

```bash
brew uninstall jailbreakit
brew untap waariss/tap
```
