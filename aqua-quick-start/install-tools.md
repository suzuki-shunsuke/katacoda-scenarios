Let's install [GitHub Official CLI](https://cli.github.com/) and [fzf](https://github.com/junegunn/fzf) with aqua.

Let's add them to `packages` in `aqua.yaml`.

`echo "- name: cli/cli@v2.2.0" >> aqua.yaml`{{execute}}

`echo "- name: junegunn/fzf@0.28.0" >> aqua.yaml`{{execute}}

`cat aqua.yaml`{{execute}}

Then run `aqua i`{{execute}}.

Congratulation! Tools are installed correctly.

`command -v gh`{{execute}}

`gh version`{{execute}}

`command -v fzf`{{execute}}

`fzf --version`{{execute}}

aqua installs tools in `${AQUA_ROOT_DIR:-${XDG_DATA_HOME:-$HOME/.local/share}/aquaproj-aqua}`.
