# bookmarks

```
usage: bookmarks [-h] [-i] [-t] [profile]

Print Firefox bookmarks to the console.

positional arguments:
  profile            name of the profile whose bookmarks are read. Glob
                     wildcards as well as `~' as a shortcut to the home
                     directory can be used. If the name contains a '/' it is
                     treated as a path to the profile folder, otherwise look
                     for a matching folder in '~/.mozilla/firefox'. Relative
                     paths can be specified by prepending './'. If no profile
                     is specified, bookmarks from the first profile matching
                     the name '*.default' are printed.

optional arguments:
  -h, --help         show this help message and exit
  -i, --ignore-lock  ignore any lock on the places.sqlite file by connecting
                     to the database with nolock=1 set. Because this program
                     does not write to the database and connects in read-only
                     mode, this should not lead to any data corruption. Enable
                     at your own risk.
  -t, --text-only    print without formatting escape characters.
```

