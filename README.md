# ast3-flood-colab
This repo hosts submodules and glue code for SERVIR AST3 work on flood.

To insure ownership of individual AST's work, the main pieces are managed via submodules (see [adding submodules section](#adding-submodules) for more information).

 * AST Lee: FIER processing

## Adding Submodules

Git allows for referencing and use of another project from within repositories, these are submodules. The code for the submodules is not hosted within the repo but rather pointed to. See the following link for more information: https://git-scm.com/book/en/v2/Git-Tools-Submodules

To add a submodule to this repo use the following commands:

```bash
$ git clone https://github.com/SERVIR/ast3-flood-colab
$ cd ast3-flood-colab
$ git submodule add <repo-address>
```

This will create a subdirectory that doesn’t track its contents, instead, Git sees it as a particular commit from that repository.

To clone this project will all code use the following command:

```bash
$ git clone --recurse-submodules https://github.com/SERVIR/ast3-flood-colab
```
