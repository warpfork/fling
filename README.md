Fling
-----

to understand: clone, cd into repo, `./fling`

---

Fling is a command launcher.

The point of Fling is to help you straighten out that heap of miscellaneous helper scripts stacking up in your project -- admit it, they exist and their numbers have been growing -- into something navigable and tab-complete'able.

Plug in *anything* (any kind of command, any binary, any language) and get subcommands, help text, and bash autocompletion support -- just by symlinking the command into the fling config dir.

Any time you would have reached for `make` (but don't really want to put up with ".PHONY" declarations and other last-century bullshit) or `rake` (but don't want to deal with the whole ruby ecosystem), reach for Fling instead.
It's pure eyewatering-but-portable bash.

Any time you would have written a "small" bash script, then watched it inevitably turn into a massive, terrifying case-switch monstrosity that now needs its own help and usage manuals... reach for Fling instead.
Fling is replacing that case-and-"do what I mean" with a scripts.d that you can navigate easily.
Fling also *is* that help and usage generator you always known you needed but could never get around to.
