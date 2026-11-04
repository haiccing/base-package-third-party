# base-package-third-party

The third-party code below mycelium, not ours: Bare's runtime and modules, the Holepunch stack, isomorphic-git, React and htm. Imported once from the development workspace (the one contact with npm), Linux x64 only, recorded in third-party.json.

A package: self-contained, its code ready to run, laid out as it is installed. Written by the package manager (`pear-full-square/pkgm-base-manager`) from the development repository; do not edit here.

- requires: nothing
- platform: linux-x64
- hash: `18c763e2dfa4009c61d1203e07bc4d4f4a20314e869e71c7f376152980fc058b`

## Holds

192 third-party modules, recorded in `third-party.json` (version, integrity, licence each).

## Installed

By the package manager, into the host's install folder (`~/.haicc/packages`), with the packages it requires; its tests run there:

```sh
node <install folder>/pear-full-square/pkgm-base-manager/cli.js install third-party --from <folder of haiccing repositories>
node <install folder>/pear-full-square/pkgm-base-manager/cli.js test third-party
```
