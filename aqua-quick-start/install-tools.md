Let's install [GitHub Official CLI](https://cli.github.com/) and [fzf](https://github.com/junegunn/fzf) with aqua.

Move to the working directory.
Let's check `aqua.yaml`.

`cd /workspace`{{execute}}

`ls -A`{{execute}}

`cat aqua.yaml`{{execute}}

Then run `aqua i`{{execute}}.

Congratulation! Tools are installed correctly.

`command -v gh`{{execute}}

`gh version`{{execute}}

`command -v fzf`{{execute}}

`fzf --version`{{execute}}

aqua installs tools in `~/.aqua` by default.
