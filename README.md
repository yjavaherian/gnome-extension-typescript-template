## Gnome 46 typescript Extension template

This is an example typescript gnome 46 extension. [reference](https://gjs.guide/extensions/development/typescript.html)

## How to use

1. fork this repo
2. change these files based on the project name and other metadata:
   - `metadata.json`
   - `package.json`
3. write your extension by editing these files:

   - `org.gnome.shell.extensions.my-extension.gschema`
   - `extension.ts`
   - `perfs.ts`

4. run `make install` to install the extension on your machine.
5. run ` dbus-run-session -- gnome-shell --nested --wayland` to open a new wayland session and debug the extension in it.
6. run `make pack` for distribution.
7. run `make clean` to remove all generated files.
