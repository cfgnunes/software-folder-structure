# Folder structure conventions

Folder structure and naming conventions for software projects.

## A common top-level directory layout

    .
    ├── data                # Data files such as icons and fonts (alternatively `resources`)
    ├── doc                 # Documentation files (alternatively `docs`)
    ├── src                 # Source files (alternatively `lib` or `app`)
    ├── test                # Automated tests (alternatively `spec` or `tests`)
    ├── LICENSE             # License file (alternatively `LICENSE.txt`, `LICENSE.md` or `COPYING`)
    └── README.md           # Read me file (alternatively `README.txt`)

### The _data_ folder

This folder contains binary files, images, icons, fonts, and other important data files for the project (assets).
Alternatively, you can put them into the `resources` folder.

    .
    ├── ...
    ├── data
    │   ├── icons           # Icons
    │   ├── images          # Images
    │   ├── fonts           # Fonts
    │   └── ...             # Etc.
    └── ...

> Examples:
[Visual Studio Code](https://github.com/microsoft/vscode) `resources`,
[Kdenlive](https://github.com/KDE/kdenlive) `data`,
[Amarok](https://github.com/KDE/amarok) `data`,
[GIMP](https://github.com/GNOME/gimp) `data`,
[Gnome Nautilus](https://github.com/GNOME/nautilus) `data`,
[Logseq](https://github.com/logseq/logseq) `resources`,
[Fritzing](https://github.com/fritzing/fritzing-app) `resources`.

### The _doc_ folder

This folder contains the documentation such as reference data into the project, which is usually stored into the `doc` or into the `docs` folder.

    .
    ├── ...
    ├── doc
    │   ├── authors.md      # Authors description
    │   ├── changelog.md    # All notable changes and versions
    │   ├── faq.md          # Frequently asked questions
    │   ├── todo.md         # To-do list to be implemented
    │   └── ...             # Etc.
    └── ...

> Examples:
[TypeScript](https://github.com/microsoft/TypeScript) `doc`,
[Go Language](https://github.com/golang/go) `doc`,
[Julia Language](https://github.com/JuliaLang/julia) `doc`,
[Java JDK](https://github.com/adoptium/jdk) `doc`,
[Kdenlive](https://github.com/KDE/kdenlive) `doc`,
[Amarok](https://github.com/KDE/amarok) `doc`,
[GIMP](https://github.com/GNOME/gimp) `docs`,
[Gnome Nautilus](https://github.com/GNOME/nautilus) `docs`,
[Node.js](https://github.com/nodejs/node) `doc`,
[PDF.js](https://github.com/mozilla/pdf.js) `docs`,
[Logseq](https://github.com/logseq/logseq) `docs`.

### The _src_ folder

The source files of a project are usually stored inside the `src` folder.
Alternatively, you can put them into the `lib` (if you're developing a library), or into the `app` folder (if your application's source files are not supposed to be compiled).

    .
    ├── ...
    ├── src
    │   ├── common          # Source files common to project
    │   ├── domain          # Source files for business logic, models
    │   ├── ui              # Source files for user interface (UI/GUI)
    │   └── ...             # Etc.
    └── ...

> Examples:
[Visual Studio Code](https://github.com/microsoft/vscode) `src`,
[TypeScript](https://github.com/microsoft/TypeScript) `src`,
[Go Language](https://github.com/golang/go) `src`,
[Julia Language](https://github.com/JuliaLang/julia) `src`,
[Java JDK](https://github.com/adoptium/jdk) `src`,
[Kdenlive](https://github.com/KDE/kdenlive) `src`,
[Amarok](https://github.com/KDE/amarok) `src`,
[Node.js](https://github.com/nodejs/node) `src`,
[PDF.js](https://github.com/mozilla/pdf.js) `src`,
[Gnome Nautilus](https://github.com/GNOME/nautilus) `src`,
[Logseq](https://github.com/logseq/logseq) `src`,
[Fritzing](https://github.com/fritzing/fritzing-app) `src`.

### The _test_ folder

Automated tests are usually placed into the `test` or, less commonly, into the `spec` or `tests` folder.

    .
    ├── ...
    ├── test
    │   ├── benchmarks      # Load and stress tests
    │   ├── integration     # Integration tests
    │   ├── unit            # Unit tests
    │   └── ...             # Etc.
    └── ...

> Examples:
[Visual Studio Code](https://github.com/microsoft/vscode) `test`,
[TypeScript](https://github.com/microsoft/TypeScript) `tests`,
[Go Language](https://github.com/golang/go) `test`,
[Julia Language](https://github.com/JuliaLang/julia) `test`,
[Java JDK](https://github.com/adoptium/jdk) `test`,
[Kdenlive](https://github.com/KDE/kdenlive) `tests`,
[Amarok](https://github.com/KDE/amarok) `tests`,
[Node.js](https://github.com/nodejs/node) `test`,
[PDF.js](https://github.com/mozilla/pdf.js) `test`,
[Gnome Nautilus](https://github.com/GNOME/nautilus) `test`,
[Fritzing](https://github.com/fritzing/fritzing-app) `test`.

### The _LICENSE_ file

If you want to share your work with others, please consider choosing an open
source license and include the text of the license into your project.
The text of a license is usually stored in the `LICENSE` (`LICENSE.txt`, `LICENSE.md` or `COPYING`) file in the root of the project.

For more information on how to choose a license for an open-source project, please refer to <https://choosealicense.com>

> Examples:
[Visual Studio Code](https://github.com/microsoft/vscode) `LICENSE.txt`,
[TypeScript](https://github.com/microsoft/TypeScript) `LICENSE.txt`,
[Go Language](https://github.com/golang/go) `LICENSE`,
[Julia Language](https://github.com/JuliaLang/julia) `LICENSE.md`,
[Java JDK](https://github.com/adoptium/jdk) `LICENSE`,
[Kdenlive](https://github.com/KDE/kdenlive) `COPYING`,
[Amarok](https://github.com/KDE/amarok) `COPYING`,
[Node.js](https://github.com/nodejs/node) `LICENSE`,
[PDF.js](https://github.com/mozilla/pdf.js) `LICENSE`,
[GIMP](https://github.com/GNOME/gimp) `LICENSE`,
[Gnome Nautilus](https://github.com/GNOME/nautilus) `LICENSE`,
[Logseq](https://github.com/logseq/logseq) `LICENSE.md`,
[Fritzing](https://github.com/fritzing/fritzing-app) `LICENSE`.

### The _README.md_ file

See a template in [README-template.md](README-template.md).

## Other common directories

    .
    ├── build               # Compiled files (or scripts for building)
    ├── dist                # Production files for distribution
    ├── po                  # Translation files for internationalization (i18n)
    └── ...

Sometimes the `build` folder is used for maintaining scripts for building (or even for packaging).
In this case, the folder contains scripts to build the software for different platforms (Windows, Linux, Mac) or different formats (Flatpak, Docker).

> Examples:
[Visual Studio Code](https://github.com/microsoft/vscode) `build`,
[GIMP](https://github.com/GNOME/gimp) `build`,
[Kdenlive](https://github.com/KDE/kdenlive) `packaging`.

## Acknowledgments

This project is inspired on works from:

- [Konstantin Tarkus](https://github.com/koistya)
- [Billie Thompson](https://github.com/PurpleBooth)
