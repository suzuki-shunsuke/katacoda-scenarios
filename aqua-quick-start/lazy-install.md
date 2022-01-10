Let's change the tool version.

`sed -i "s|cli/cli@v2\.2\.0|cli/cli@v2.1.0|" aqua.yaml`{{execute}}

`cat aqua.yaml`{{execute}}

Then execute GitHub CLI.

`gh version`{{execute}}

You find that `cli/cli@v2.1.0` is installed automatically.
You don't have to run `aqua i` explicitly.
We call this feature as `Lazy Install`.

Note that `Lazy Install` doesn't work if the symbolic link isn't created in `${AQUA_ROOT_DIR:-${XDG_DATA_HOME:-$HOME/.local/share}/aquaproj-aqua}/bin` yet.

`tfmigrator --version`{{execute}}
