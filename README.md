# Awesome Janet

Curated list of libraries and tooling for the Janet programming
language: https://janet-lang.org

If you have a library or package you're working on, or have come
across one, feel free to make a PR.

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
        - [Client](#client)
    - [Game Dev](#game-dev)
        - [Graphics](#graphics)
    - [GUI](#gui)
    - [Database](#database)
    - [Serialization](#serialization)
    - [Random](#random)
- [Related tooling/projects](#related-toolingprojects)

<!-- markdown-toc end -->

# Editors

This section doesn't need much explanation.

## Emacs

- [janet-mode](https://github.com/ALSchwalm/janet-mode) Major mode for
editing Janet files
- [inf-janet](https://github.com/velkyel/inf-janet) Comint mode for
wrapping an inferior Janet process

## Vim

- [janet.vim](https://github.com/janet-lang/janet.vim) Syntax files for Janet in Vim
- [conjure/netrepl](https://github.com/Olical/conjure/wiki/Quick-start:-Janet-(netrepl))
  NeoVIM Netrepl

## VS

- [vscode-janet](https://github.com/janet-lang/vscode-janet) Visual
Studio Code plugin (Syntax highlighting, Eval sexp/file)

# JPM installable packages

JPM (Janet Package Manager) is the official package manager of Janet
and comes with the Janet distribution.

## Package Management

- [pkgs](https://github.com/janet-lang/pkgs) The official package listing for Janet.
- [hermes](https://github.com/andrewchambers/hermes) Nix/Guix like
  software environment manager.

## Web

### Frameworks

- [Joy](https://github.com/joy-framework/joy) Full stack web framework
- [Chidi](https://github.com/good-place/chidi) API oriented web framework (WIP).

### Server

- [Circlet](https://github.com/janet-lang/circlet) HTTP and networking
library with a Clojure Ring-like abstraction.

### Client

- [jurl](https://github.com/sepisoad/jurl) Janet bindings for libcurl

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
- [janet-redis](https://github.com/andrewchambers/janet-redis) Redis bindings
- [tahani](https://github.com/good-place/tahani) LevelDB bindings
- [mansion](https://github.com/good-place/mansion) LevelDB store abstraction

## Serialization

- [json](https://github.com/janet-lang/json) JSON library
- [jdn](https://github.com/andrewchambers/janet-jdn) Janet Data Notation library

## Random

- [Spork](https://github.com/janet-lang/spork) Various Janet utility
  modules (includes a code formatter).
- [janet-sh](https://github.com/andrewchambers/janet-sh) Shell like short hands for running commands in janet code.

# Related tooling/projects

Projects that are not necessarily written in Janet or directly in the
Janet/JPM ecosystem, but are of potential interest to the Janet
audience and have direct usage for Janet projects.

- [Puny GUI](https://github.com/ahungry/puny-gui) Pre-built
cross-platform distribution of Janet runtime with extras (native GUI,
libcurl, sqlite)
- [swig (add-janet-branch)](https://github.com/ahungry/swig/tree/feature/Add-janet) SWIG
  auto-generates bindings from C header files and/or SWIG interface
  files, and produces the appropriate Janet-wrap bindings (tested/used
  on IUP, libcurl, libcairo and more).
