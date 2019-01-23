# dwm

My personal setup of dwm (https://git.suckless.org/dwm/) including some patches

## Update dwm sources [WIP]

### Variant 1

```
git checkout -b  mergetest -t origin/master
git fetch dwm
git merge dwm/master --allow-unrelated-histories
```

Then build it using `make` and merge/push to master if it works.

### Variant 2

```
git fetch dwm/master
git checkout -b update -t dwm/master
```

Then apply all patches, build it, test it and merge it into master.
