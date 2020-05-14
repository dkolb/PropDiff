# PropDiff

To compile:

```shell
javac PropDiff.java
```

To run:
```shell
#!/bin/bash
# executable file called propdiff
java -classpath $HOME/path/to/propdiff PropDiff $*
```

To use as a diftool:

```conf
#~/.gitconfig
[difftool "propdiff"]
  cmd = propdiff -d12 "$LOCAL" "$REMOTE" -f -
```

```
$ git difftool --tool=propdiff some.properties
```

## Dev Notes

Is there a better way?  Sure, but this was at the top of the google search results so it's what you get.
