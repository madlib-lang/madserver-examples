# Madserver example

This project is an example use case of consumption and usage of the madlib wrapper for expressjs available here: [https://github.com/open-sorcerers/madserver](https://github.com/open-sorcerers/madserver).


## Instructions

To run it you should have madlib and nodejs installed and run the following:

```bash
madlib install
madlib compile -i src/Main.mad
node build/Main.mjs
```

Here is the expected output:
```shell
$ ls
README.md         madlib.json       package-lock.json src
$ madlib install
Installing dependencies ...
Packages to install:
  - Madserver
nodejs modules installed for 'Madserver'
package Madserver installed
$ ls
README.md         madlib.json       madlib_modules    node_modules      package-lock.json src
$ madlib compile -i src/Main.mad
$ ls
README.md         build             madlib.json       madlib_modules    node_modules      package-lock.json src
$ node build/Main.mjs
Server running on port 3000...
```
