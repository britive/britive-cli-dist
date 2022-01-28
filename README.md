# britive-cli-dist
Static NPM packaging of the Britive CLI
### Installing from `.tgz` package:
Steps to install:
1. Download the `britive-cli-1.2.6.tgz` from the path: https://github.com/britive/britive-cli-dist/releases/download/v1.2.6/britive-cli-1.2.6.tgz
```
$ sha256sum britive-cli-1.2.6.tgz
3079299bd172388b409b2caefabbe5ad969b7f576208925924879007c1eae8b4  britive-cli-1.2.6.tgz
```
2. Install the package from the path where it is downloaded:
```sh-session
$ npm install -g <path of .tgz>
```
3. You can use the `britive` commands post installation:
```
$ britive COMMAND
running command...
$ britive (-v|--version|version)
britive-cli/1.2.6 linux-x64 node-v14.15.0
$ britive --help [COMMAND]
USAGE
$ britive COMMAND
...
```
More information can be found at https://docs.britive.com/docs/command-line-features
