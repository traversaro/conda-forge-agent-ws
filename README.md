# conda-forge-agent-ws

Ready-to-use workspace for AI agents doing conda-forge maintenance work.

## Overview

This repo is a [pixi](https://pixi.sh/) workspace pre-configured with the tools and agent skills needed to work on conda-forge feedstocks. Instead of vendoring skill markdown files directly into git, skills are managed as proper conda packages via [pixi-skills](https://github.com/pavelzw/pixi-skills).

## Getting started

Install pixi environments and skills:

```sh
pixi run pixi skills manage
```

