# Cannox's space

This is a personal website built with [Hugo](https://gohugo.io/) using the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Installation

### macOS with Homebrew

Install Hugo and Git:

```bash
brew install hugo git
```

Clone the repository and initialize the PaperMod theme submodule:

```bash
git clone https://github.com/cannox227/cannox227.github.io.git
cd cannox227.github.io
git submodule update --init --recursive
```

Verify that the site builds:

```bash
hugo --minify
```

Start the development server:

```bash
hugo server
```

Open [http://localhost:1313/](http://localhost:1313/) in your browser.

## Existing checkout

If the repository is already cloned:

```bash
cd cannox227.github.io
git pull
git submodule update --init --recursive
hugo server
```

## Theme updates

To update the PaperMod submodule:

```bash
git submodule update --remote --merge
```
