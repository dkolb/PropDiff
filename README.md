# PropDiff

To compile:

```shell
javac PropDiff.java
```

To run:
```shell
#!/bin/bash
# executable file called propdiff
java -classpath $HOME/path/to/propdiff.class PropDiff $*
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
