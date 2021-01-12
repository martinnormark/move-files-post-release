# move-files-post-release
Test action that moves specific files after a release.

When run, files in `./files` dir that starts with `file[0-9` will be removed and the lines in `./index.json` that contains the same pattern will be removed.
