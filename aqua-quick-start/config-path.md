aqua finds configuration files from the current directory to the root directory.

Let's create the directory `zoo` and move to it.

`mkdir zoo`{{execute}}

`cd zoo`{{execute}}

In the current directory, `aqua.yaml` doesn't exist but you can execute GitHub CLI because aqua reads `../aqua.yaml`.

`gh version`{{execute}}

aqua reads configuration files until the tool is found.
tfmigrator isn't found in `../aqua.yaml`, but is found in `../../aqua.yaml`.

`tfmigrator -v`{{execute}}

If the executed command isn't found in configuration files and the tool isn't installed outside aqua,
the command fails.

`cd /tmp`{{execute}}

`gh version`{{execute}}
