# homebysix-recipes

My recipes for AutoPkg. If you use them, click the Star button above to show your support!

Big thanks to [@rtrouton](https://github.com/rtrouton) for writing the [AutoPkgr](https://github.com/lindegroup/autopkgr) recipes.


## Installation

To use, run this command:

```
autopkg repo-add homebysix-recipes
```

If you previously subscribed to my old repo, you'll need to remove that one and add this new one:

```
autopkg repo-delete https://github.com/homebysix/homebysix-autopkg-recipes.git
autopkg repo-add homebysix-recipes
```


## Dependencies

Some of my recipes have parent recipes that live in another repo. To add them all in one shot, here is the command you'll need:

```
autopkg repo-add recipes eholtam-recipes hansen-m-recipes jaharmi-recipes jleggat-recipes jps3-recipes keeleysam-recipes rustymyers-recipes
```


## Submissions

Forks/pulls/issues are welcome. I'm always tweaking.
