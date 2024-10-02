# Bash Scripts for Linux

## Description

This is a collection of bash scripts that i've been building to automate some tasks on my Linux machines.

- They are **not** intended to work on every machine, but you can use them as a reference to build your own scripts.
- They are meant to be used on Ubuntu ^20.04 LTS.

## How to use

- Clone this repository to your machine.
- Give the scripts execution permission with `chmod +x -R /path/to/scripts`.
- Update `~/.bashrc`, `~/.zshrc`, etc. with the following line: `export PATH=$PATH:/path/to/scripts`.
- Restart your terminal.

## Scripts
- [**`fonts-install`**](fonts-install) - Install TTF fonts from a directory and restart the font cache.
- [**`jina`**](jina) - Pass a URL to https://r.jina.ai/ and get the text from the page.
- [**`jina-news`**](jina-news) - Pass a URL to `jina | llm | glow` to get an AI response breaking down the news article.
- [**`jina-tech`**](jina-tech) - Pass a URL to `jina | llm` to get an AI response with a more in-depth technical breakdown of the news article, blog post, spec, etc.
- [**`basher`**](basher) - A quick fzf wrapper to search the bash scripts in this repository.