# Awesome Janet

Curated list of libraries and tooling for the Janet programming
language: https://janet-lang.org

<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [Awesome Janet](#awesome-janet)
- [Editors](#editors)
    - [Emacs](#emacs)
    - [Vim](#vim)
    - [VS](#vs)
- [JPM installable packages](#jpm-installable-packages)
    - [Package Management](#package-management)
    - [Web](#web)
        - [Frameworks](#frameworks)
        - [Server](#server)
    - [Game Dev](#game-dev)
        - [Graphics](#graphics)
    - [GUI](#gui)
    - [Database](#database)
    - [Serialization](#serialization)
    - [Random](#random)
- [Related tooling/projects](#related-toolingprojects)

<!-- markdown-toc end -->

# Editors

## Emacs

- [janet-mode](https://github.com/ALSchwalm/janet-mode) Major mode for
editing Janet files
- [inf-janet](https://github.com/velkyel/inf-janet) Comint mode for
wrapping an inferior Janet process

## Vim

- [janet.vim](https://github.com/janet-lang/janet.vim) Syntax files for Janet in Vim

## VS

- [vscode-janet](https://github.com/janet-lang/vscode-janet) Visual
Studio Code plugin (Syntax highlighting, Eval sexp/file)

# JPM installable packages

## Package Management

- [pkgs](https://github.com/janet-lang/pkgs) The official package listing for Janet.
- [hermes](https://github.com/andrewchambers/hermes) Nix/Guix like
  software environment manager with Janet/jpm support.

## Web

### Frameworks

- [Joy](https://github.com/joy-framework/joy) Full stack web framework

### Server

- [Circlet](https://github.com/janet-lang/circlet) HTTP and networking
library with a Clojure Ring-like abstraction.

## Game Dev

### Graphics

- [Jaylib](https://github.com/janet-lang/jaylib) Janet bindings to Raylib.

## GUI

- [janetui](https://github.com/janet-lang/janetui) Bindings to libui
- [webview](https://github.com/janet-lang/webview) Electron-like
  webview bindings.

## Database

- [sqlite3](https://github.com/janet-lang/sqlite3) Sqlite bindings
- [janet-pq](https://github.com/andrewchambers/janet-pq) Postgres bindings

## Serialization

- [json](https://github.com/janet-lang/json) JSON library

## Random

- [Spork](https://github.com/janet-lang/spork) Various Janet utility modules.
- [janetsh](https://github.com/andrewchambers/janetsh) A new system shell that uses the Janet programming language for high level scripting while also supporting the things we love about sh.

# Related tooling/projects

- [Puny GUI](https://github.com/ahungry/puny-gui) Pre-built
cross-platform distribution of Janet runtime with extras (native GUI,
libcurl, sqlite)
