# Developer Tools for Mac

This document lists essential tools for developers.

## Homebrew

[Homebrew](https://brew.sh/) is a package manager for macOS that simplifies the installation of software.

Installation:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Git

[Git](https://git-scm.com/) is a free and open source distributed version control system.

Installation:
```bash
brew install git
```

## Kubernetes CLI (kubectl)

[Kubectl](https://kubernetes.io/docs/reference/kubectl/overview/) is a command line interface for running commands against Kubernetes clusters.

Installation:
```bash
brew install kubectl
```

Remember to keep your tools updated with `brew upgrade`.

## Mob

[Mob.sh](https://mob.sh/) is a simple tool that facilitates swift git handovers in a mob programming setup.

Installation:
```bash
brew install remotemobprogramming/brew/mob

