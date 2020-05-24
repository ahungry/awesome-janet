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
    - [Continuous Integration](#continuous-integration)
        - [GitHub Actions](#github-actions)
    - [Database](#database)
    - [Game Dev](#game-dev)
        - [Graphics](#graphics)
    - [GUI](#gui)
    - [Package Management](#package-management)
    - [Serialization](#serialization)
    - [Testing](#testing)
    - [Web](#web)
        - [Client](#client)
        - [Frameworks](#frameworks)
        - [Frontend/JS](#frontendjs)
        - [Server](#server)
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

- [janet.vim](https://github.com/janet-lang/janet.vim) Syntax files for
  Janet in Vim
- [Conjure](https://github.com/Olical/conjure) Interactive development
  environment for Neovim ([use with Janet](https://github.com/Olical/conjure/wiki/Quick-start:-Janet-(netrepl)))

## VS

- [vscode-janet](https://github.com/janet-lang/vscode-janet) Visual
Studio Code plugin (Syntax highlighting, Eval sexp/file)

# JPM installable packages

JPM (Janet Package Manager) is the official package manager of Janet
and comes with the Janet distribution.

## Continuous Integration

### GitHub Actions

- [build.yaml](https://gist.github.com/pyrmont/565756c9a68879a2fca2966ca3e74fa3)
  A simple workflow for GitHub Actions that will download, set up and
  test a project

## Database

- [sqlite3](https://github.com/janet-lang/sqlite3) Sqlite bindings
- [janet-pq](https://github.com/andrewchambers/janet-pq) Postgres bindings
- [janet-redis](https://github.com/andrewchambers/janet-redis) Redis bindings
- [tahani](https://github.com/good-place/tahani) LevelDB bindings
- [mansion](https://github.com/good-place/mansion) LevelDB store abstraction

## Game Dev

### Graphics

- [Jaylib](https://github.com/janet-lang/jaylib) Janet bindings to Raylib.

## GUI

- [janetui](https://github.com/janet-lang/janetui) Bindings to libui
- [webview](https://github.com/janet-lang/webview) Electron-like
  webview bindings.

## Package Management

- [pkgs](https://github.com/janet-lang/pkgs) The official package listing for Janet.
- [hermes](https://github.com/andrewchambers/hermes) Nix/Guix like
  software environment manager.

## Serialization

- [json](https://github.com/janet-lang/json) JSON library
- [jdn](https://github.com/andrewchambers/janet-jdn) Janet Data Notation library

## Testing

- [Testament](https://github.com/pyrmont/testament) A testing library
  inspired by clojure.test
- [tester](https://github.com/joy-framework/tester) A testing library
  extracted from the Joy project

## Web

### Client

- [jurl](https://github.com/sepisoad/jurl) Janet bindings for libcurl

### Frameworks

- [Joy](https://github.com/joy-framework/joy) Full stack web framework
- [Chidi](https://github.com/good-place/chidi) API oriented web framework (WIP).

### Frontend/JS

- [janetscript](https://github.com/ahungry/janetscript) Janet to JS Transpiler

### Server

- [Circlet](https://github.com/janet-lang/circlet) HTTP and networking
library with a Clojure Ring-like abstraction.

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
