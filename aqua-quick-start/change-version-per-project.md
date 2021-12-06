aqua supports changing the tool versions per project.

`cat foo/aqua.yaml`{{execute}}

`cat bar/aqua.yaml`{{execute}}

`cd foo`{{execute}}

`gh version`{{execute}}

`cd ../bar`{{execute}}

`gh version`{{execute}}

The version of `gh` is changed seamlessly.

You can install multiple versions in the same laptop and switch the version by project.

`cd -`{{execute}}

`gh version`{{execute}}

`cd -`{{execute}}

`gh version`{{execute}}
