aqua finds configuration files from the current directory to the root directory.

`mkdir zoo`{{execute}}

`gh version`{{execute}}

aqua reads configuration files until the tool is found.
tfmigrator isn't found in `../aqua.yaml`, but is found in `../../aqua.yaml`.

`tfmigrator -v`{{execute}}

If the configuration file isn't found and the tool isn't installed outside aqua,
the command fails.

`cd /tmp`{{execute}}

`gh version`{{execute}}
