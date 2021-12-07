# terminal

this repo is to record useful terminal commands on random daily problems such as upgrading softwares and OS

### [VS Code C Error - Invalid Active Developer Path](https://stackoverflow.com/questions/69795650/vs-code-c-error-invalid-active-developer-path)

When upgrading your Mac OS, sometimes the code command-line tools stop working. This can be resolved by running this in the terminal:

```bash
xcode-select --switch /Applications/Xcode.app/Contents/Developer
```

Also make sure that you've upgraded to the latest version of xcode.
