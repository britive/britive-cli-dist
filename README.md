# britive-cli-dist
Static NPM packaging of the Britive CLI
### Installing from `.tgz` package:
Steps to install:
1. Download britive-cli-<version>.tgz from https://github.com/britive/britive-cli-dist/releases/
```
$ sha256sum britive-cli-<version>.tgz
00f4e491f2effb2b9feaf259f0e1c4710409c0ef1cd1e018a58276119bc7df67  britive-cli-1.2.8.tgz
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
britive-cli/<version> ...
$ britive --help [COMMAND]
USAGE
$ britive COMMAND
...
```
More information can be found at https://docs.britive.com/docs/command-line-features
