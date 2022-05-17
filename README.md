# britive-cli-dist
Static NPM packaging of the Britive CLI
### Installing from `.tgz` package:
Steps to install:
1. Download britive-cli-<version_number>.tgz from https://github.com/britive/britive-cli-dist/releases/
```
$ sha256sum britive-cli-<version_number>.tgz
cfaab17b2b942ed0ab58fc66fbb239c307dbd38b5671e91ad5131e6aa570be1e  britive-cli-2.1.0.tgz
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
britive-cli/<version_number> ...
$ britive --help [COMMAND]
USAGE
$ britive COMMAND
...
```
More information can be found at https://docs.britive.com/docs/command-line-features
