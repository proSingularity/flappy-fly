[![Build Status](https://travis-ci.com/proSingularity/flappy-fly.svg?branch=master)](https://travis-ci.com/proSingularity/flappy-fly)

# Flappy Fly

**Play now at [prosingularity.github.io/flappy-fly](https://prosingularity.github.io/flappy-fly).**

Clone of [Flappy bird](https://en.wikipedia.org/wiki/Flappy_Bird), a game developed by Dong Nguyen that went viral in early 2014

## State Machine

[![](https://mermaid.ink/img/eyJjb2RlIjoic3RhdGVEaWFncmFtXG5cdFsqXSAtLT4gTG9hZFxuXHRMb2FkIC0tPiBTdGFydFxuXHRTdGFydCAtLT4gUGxheVxuXHRQbGF5IC0tPiBEZWFkXG5cdERlYWQgLS0-IFN0YXJ0XG5cdFx0XHRcdFx0IiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjpmYWxzZX0)](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoic3RhdGVEaWFncmFtXG5cdFsqXSAtLT4gTG9hZFxuXHRMb2FkIC0tPiBTdGFydFxuXHRTdGFydCAtLT4gUGxheVxuXHRQbGF5IC0tPiBEZWFkXG5cdERlYWQgLS0-IFN0YXJ0XG5cdFx0XHRcdFx0IiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjpmYWxzZX0)

## Getting started

### Installing

Assumes you have globally installed

- git
- node.js

Clone the git repository

```bash
git clone https://github.com/proSingularity/a-flappy-bird-clone.git
```

Install, test and start:

```bash
npm run sanity-check
```

### Building and Running

Perform a quick build (bundle.js) and start server:

```bash
npm run dev
```

In your browser, navigate to [localhost:8080](http://localhost:8080).

## Debugging

```bash
npm run dev
# STEP: you can close the window that opens automatically
# STEP: Set a breakpoint in VS CODE
# STEP: Start 'Chrome' debug config in VS Code
# STEP: Maybe reload the window
# STEP: Trigger the breakpoint
```

## Deployment

Continuous deployment to github pages [https://prosingularity.github.io/flappy-fly/](https://prosingularity.github.io/flappy-fly/) is performed on each push to `master`.

See [.travis.yml](.travis.yml).

## External Resources

- [Phaser 3 Framework](https://github.com/photonstorm/phaser)
- [Phaser 3 Docs with TypeScript Definition File](https://github.com/photonstorm/phaser3-docs)
- [Phaser 3 Online Docs](https://photonstorm.github.io/phaser3-docs/index.html)
- [Phaser 3 Official Examples](https://github.com/photonstorm/phaser3-examples)
- [Cheat sheets](https://github.com/digitsensitive/phaser3-typescript/blob/master/cheatsheets)
- [Template Project - Phaser3 with TypeScript](https://github.com/digitsensitive/phaser3-typescript)

## Helpful tools

- [Pixel Art Maker](http://pixelartmaker.com/)
- [Leshy SpriteSheet Tool](https://www.leshylabs.com/apps/sstool)
- [Littera](http://kvazars.com/littera)
- [MagicTools](https://github.com/ellisonleao/magictools)
- [Tiled](https://www.mapeditor.org)
