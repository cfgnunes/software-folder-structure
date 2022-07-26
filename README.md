# Folder structure conventions

Folder structure and naming conventions for software projects.

## A common top-level directory layout

    .
    ├── build       # Installer files (alternatively `dist`)
    ├── data        # Data files such as icons and images (alternatively `resource`)
    ├── docs        # Documentation files (alternatively `doc`)
    ├── po          # Internationalization files (alternatively `msg`)
    ├── src         # Source files (alternatively `lib` or `app`)
    ├── test        # Automated tests (alternatively `spec` or `tests`)
    ├── LICENSE     # License file (alternatively `LICENSE.txt`, `LICENSE.md` or `COPYING`)
    └── README.md   # Read-me file (alternatively `README.txt`)

### `build` folder

This folder contains installer scripts or even binary files for distribution.
Alternatively, you can put them into the `dist`.

### `data` folder

This folder contains binary files, images, icons and other important data files for the project.

### `docs` folder

This folder contains the documentation such as reference data into the project, which is usually stored into the `docs` or, less commonly, into the `doc` folder.

### `po` folder

The `.po` files for software translation (internationalization) are usually stored inside the `po` folder or, less commonly, into the `msg` folder.

### `src` folder

The source files of a project are usually stored inside the `src` folder.
Alternatively, you can put them into the `lib` (if you're developing a library), or into the `app` folder (if your application's source files are not supposed to be compiled).

### `test` folder

Automated tests are usually placed into the `test` or, less commonly, into the `spec` or `tests` folder.

### `LICENSE` file

If you want to share your work with others, please consider choosing an open
source license and include the text of the license into your project.
The text of a license is usually stored in the `LICENSE` (`LICENSE.txt`, `LICENSE.md` or `COPYING`) file in the root of the project.

For more information on how to choose a license for an open-source project, please refer to <https://choosealicense.com>

### `README.md` file

See a template in.
