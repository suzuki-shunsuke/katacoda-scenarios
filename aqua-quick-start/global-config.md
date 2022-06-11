aqua finds the configuration files from the current directory to the root directory.

`pwd`{{execute}}

`gh version`{{execute}}

If you want to install tools regardless the current directory,
let's add the global configuration.
Global Configuration file paths are configured with the environment variable `AQUA_GLOBAL_CONFIG`. You can change the file path freely.

`export AQUA_GLOBAL_CONFIG="${AQUA_GLOBAL_CONFIG:-}:${XDG_CONFIG_HOME:-$HOME/.config}/aquaproj-aqua/aqua.yaml"`{{execute}}

`mkdir -p ${XDG_CONFIG_HOME:-$HOME/.config}/aquaproj-aqua`{{execute}}

`cp /workspace/global/aqua.yaml ${XDG_CONFIG_HOME:-$HOME/.config}/aquaproj-aqua`{{execute}}

`cat ${XDG_CONFIG_HOME:-$HOME/.config}/aquaproj-aqua/aqua.yaml`{{execute}}

`gh version`{{execute}}
