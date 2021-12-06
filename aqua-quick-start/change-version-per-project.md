aqua supports changing the tool versions per project.

In the workspace, there are two directories `foo` and `bar`.
Please check `aqua.yaml` in these directories.

`cat foo/aqua.yaml`{{execute}}

`cat bar/aqua.yaml`{{execute}}

Let's move to `foo` and `bar` and run GitHub CLI.

`cd foo`{{execute}}

`gh version`{{execute}}

`cd ../bar`{{execute}}

`gh version`{{execute}}

The version of GitHub CLI is changed seamlessly.
You can install multiple versions in the same laptop and switch the version by project.

`cd -`{{execute}}

`gh version`{{execute}}

`cd -`{{execute}}

`gh version`{{execute}}
