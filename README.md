# britive-cli-dist
Static NPM packaging of the Britive CLI
### Installing from `.tgz` package:
Steps to install:
1. Download britive-cli-<version_number>.tgz from https://github.com/britive/britive-cli-dist/releases/
```
$ sha256sum britive-cli-<version_number>.tgz
da1585100117a7291e032798c7ed8780f917d614dea37afd29cb74bab3db4b29  britive-cli-2.0.1.tgz
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
