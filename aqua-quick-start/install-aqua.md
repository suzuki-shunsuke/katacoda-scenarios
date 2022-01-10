aqua is a CLI tool to install CLI tools with declarative YAML configuration.
In this quick start, let's install aqua and install tools with aqua.

Install aqua with ([aqua-installer](https://github.com/aquaproj/aqua-installer)).

`curl -sSfL https://raw.githubusercontent.com/aquaproj/aqua-installer/v0.5.0/aqua-installer | bash`{{execute}}

Confirm if aqua is installed correctly.

`aqua -v`{{execute}}

Add `~/.aqua/bin` to the environmenet variable `PATH`.

`export PATH=$HOME/.aqua/bin:$PATH`{{execute}}
