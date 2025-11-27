[comment]: # (Set the theme:)
[comment]: # (THEME = black)
[comment]: # (CODE_THEME = base16/zenburn)
[comment]: # (The list of themes is at https://revealjs.com/themes/)
[comment]: # (The list of code themes is at https://highlightjs.org/)

[comment]: # (Pass optional settings to reveal.js:)
[comment]: # (controls: true)
[comment]: # (keyboard: true)
[comment]: # (markdown: { smartypants: true })
[comment]: # (hash: false)
[comment]: # (respondToHashChanges: false)
[comment]: # (Other settings are documented at https://revealjs.com/config/)

Rasmus | 27.11.2025

# Local k8s

[comment]: # (!!!)

## Bring your own tools
* Any terminal
* bash || zsh
* git
* containerd

[comment]: # (!!!)

## Install the rest
```shell
curl -fsSL https://get.jetify.com/devbox | bash
git clone https://github.com/RasmusSoot/local-k8s.git
cd local-k8s
devbox shell
devbox run just-work
```
