---
runme:
  id: 01HGZZ742BM6RYJ8ZV19GETSVX
  version: v3
---

# Shebang demo

## Bash commands

This cell demonstrates the use of the `which` command to locate the executables for `runme` and `go` in the system's PATH.

```sh {"id":"01J4HK8BGKHAKYYF8G36NKS455"}
which runme
which go
```

This cell demonstrates setting and echoing environment variables in a shell.

```sh {"category":"exports","id":"01J4HK8BGKHAKYYF8G38ZNTMB3","interactive":"true","interpreter":"","name":"export-vars","promptEnv":"auto","terminalRows":"3"}
export DOG_NAME="Roscoe"
export FOO_BAR="BAZ LOO"
export NAKED="naked"
export NEW_VAR="Here is a new var"
export NEW_VAR2="new var 2"
echo "Foo"
echo $DOG_NAME
```

This cell demonstrates setting and echoing environment variables from a previous cell

```sh {"id":"01J4HK8BGKHAKYYF8G3A7HBQ4C","interpreter":"sh"}
echo $DOG_NAME
```

## JavaScript

Example of a JavaScript script that prints the current date and time. The script will exit with a status code of 1.

```js {"excludeFromRunAll":"true","id":"01J4HK8BGKHAKYYF8G3CB017E7","interactive":"true","name":"demo-js","terminalRows":"2"}
console.log("Always bet on JS!, " + new Date().toISOString())
process.exit(1)
```

## Python

Print the value of the environment variable `DOG_NAME` in a Python script.

```python {"id":"01J4HK8BGKHAKYYF8G3CTSAC4T","interpreter":"/usr/bin/python3","name":"demo-py","terminalRows":"2"}
import datetime
import os

now = datetime.datetime.now()

def say_hello():
  print(" Hello world from Python, " + now.isoformat(sep='T',timespec='auto'))

say_hello()

```