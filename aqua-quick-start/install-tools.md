Let's install [GitHub Official CLI](https://cli.github.com/) and [fzf](https://github.com/junegunn/fzf) with aqua.

Let's move to the working directory and check `aqua.yaml`.

`cd /workspace`{{execute}}

`cat aqua.yaml`{{execute}}

Then run `aqua i`{{execute}}.

Congratulation! Tools are installed correctly.

`command -v gh`{{execute}}

`gh version`{{execute}}

`command -v fzf`{{execute}}

`fzf --version`{{execute}}

aqua installs tools in `~/.aqua` by default.
