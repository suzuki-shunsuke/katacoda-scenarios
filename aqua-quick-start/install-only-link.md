You added [tfmigrator/cli](https://github.com/tfmigrator/cli) in the step `Search packages`, but it isn't installed yet.

`tfmigrator -v`{{execute}}

Let's run `aqua i -l`{{execute}}.

The command would exit immediately, because the tool isn't downloaded and installed yet.

The command `aqua i` installs all tools at once.
But when the option `-l` is set, `aqua i` creates only symbolic links in `${AQUA_ROOT_DIR:-${XDG_DATA_HOME:-$HOME/.local/share}/aquaproj-aqua}/bin` and skips downloading and installing tools.

Even if downloading and installing are skipped, you can execute the tool thanks for `Lazy Install`.

`tfmigrator -v`{{execute}}

`-l` option is useful for local development, because you can install only tools which are needed for you.
