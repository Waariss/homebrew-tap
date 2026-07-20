# Waariss Homebrew Tap

Homebrew formulas for command-line tools maintained by Waris Damkham.

## Available formulas

| Formula | Description |
|---|---|
| `jailbreakit` | iOS pentest lab setup helper for authorized security testing |
| `whitebox-secure-scan` | Offline white-box secure-code triage for penetration testers |

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

## Install whitebox-secure-scan

Install directly:

```bash
brew install waariss/tap/whitebox-secure-scan
```

Verify the installation:

```bash
whitebox-secure-scan version
whitebox-secure-scan doctor
```

Or tap the repository first:

```bash
brew tap waariss/tap
brew install whitebox-secure-scan
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
brew uninstall whitebox-secure-scan
```

Remove the tap entirely when no formulas from it are installed:

```bash
brew untap waariss/tap
```
