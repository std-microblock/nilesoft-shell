[![Build](../../actions/workflows/build.yml/badge.svg)](../../actions/workflows/build.yml)

# Morpthis Shell
Powerful manager for the Windows File Explorer context menu.
<br>

<p align="center">
 <img src="/packages/assets/logo-256.png">
 <br>
 <br>
</p>

## Details
<p>
Morpthis Shell is a context menu extender that lets you handpick the items to integrate into the Windows File Explorer context menu, create custom commands to access all your favorite web pages, files, and folders, and launch any application directly from the context menu.<br>
It also provides you a convenient solution to modify or remove any context menu item added by the system or third-party software.
</p>

Features
------------------
* Lightweight, portable, and relatively easy to use.
* Fully customize the appearance.
* Adding new custom items such as (sub-menu, menu-items, and separator).
* Modify or remove items that already exist.
* Support all file system objects, including files, folders, desktop, and the taskbar.
* Support expressions syntax. with built-in functions and predefined variables.
* Support colors, glyphs, SVG, embedded icons, and image files such as .ico, .png or .bmp.
* Support search and filter.
* Support for complex nested menus.
* Support multiple columns.
* Quickly and easily configure file in plain text.
* Minimal resource usage.
* No limitations.


Requirements
------------------
  * Microsoft Windows 7/8/10/11 


Documentation
------------------
Browse the [documentation](docs/). The configuration file is `morpthis.nss`, next to `morpthis.exe`.


Download
------------------
Builds are produced by GitHub Actions: open the [Build workflow](../../actions/workflows/build.yml),
pick the latest successful run and download `morpthis-shell-x64` (or `morpthis-shell-x86`).

Register from an elevated command prompt in the extracted folder:

```
morpthis -register -restart
```

and unregister with `morpthis -unregister -restart`.

> Morpthis Shell uses its own COM IDs, file names and registry keys, so it can be installed
> side by side with Nilesoft Shell. Builds from before the rebrand (`shell.exe` / `shell.dll`)
> must be unregistered with their own `shell -unregister` before switching.

Screenshots
------------------
<p align="center">
<img src="/screenshots/folder-back.png"><img src="/screenshots/file-manage.png"><br>
<img src="/screenshots/view.png"><img src="/screenshots/edit.png"><br>
<img src="/screenshots/terminal.png"><img src="/screenshots/taskbar.png"><br>
<img src="/screenshots/goto2.png"><img src="/screenshots/gradient.png"><br>
<img src="/screenshots/acrylic.png"><br>

<br>
<br>
</p>

Credits
------------------
Morpthis Shell is a fork of [Nilesoft Shell](https://github.com/moudey/Shell) by Nilesoft,
released under the MIT License. See [LICENSE](LICENSE).
