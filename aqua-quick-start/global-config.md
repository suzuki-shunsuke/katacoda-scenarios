aqua finds the configuration files from the current directory to the root directory.

`pwd`{{execute}}

`gh version`{{execute}}

If you want to install tools regardless the current directory,
let's add the global configuration `~/.aqua/global/aqua.yaml`.

`mkdir ~/.aqua/global`{{execute}}

`cp global-config/aqua.yaml ~/.aqua/global`{{execute}}

`gh version`{{execute}}

You can add Global Configuration by the environment variable `AQUA_GLOBAL_CONFIG`.
