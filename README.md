Demonstration repo for Yarn issues:

- https://github.com/yarnpkg/yarn/issues/4334
- https://github.com/yarnpkg/yarn/issues/4348

To demonstrate 4334 (failure message when removing package from workspace):

```sh
$ yarn run remove-bug
```

To demonstrate 4348 (`yarn.lock` entries pruned when adding to root):

```sh
$ cat yarn.lock
$ yarn run add-bug
$ cat yarn.lock
```
