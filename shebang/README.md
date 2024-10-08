---
runme:
  id: 01HGZZ742BM6RYJ8ZV19GETSVX
  version: v3
---

# Shebang demo

```sh {"id":"01J4HK8BGKHAKYYF8G36NKS455"}
which runme
which go
```

```sh {"category":"exports","id":"01J4HK8BGKHAKYYF8G38ZNTMB3","interactive":"true","interpreter":"","name":"export-vars","promptEnv":"auto","terminalRows":"3"}
export DOG_NAME="Roscoe"
export FOO_BAR="BAZ LOO"
export NAKED="naked"
export NEW_VAR="Here is a new var"
export NEW_VAR2="new var 2"
echo "Foo"
echo $DOG_NAME
```

```sh {"id":"01J4HK8BGKHAKYYF8G3A7HBQ4C","interpreter":"pwsh"}
echo $DOG_NAME
```

#### JavaScript

```js {"excludeFromRunAll":"true","id":"01J4HK8BGKHAKYYF8G3CB017E7","name":"demo-js","terminalRows":"2"}
console.log("Always bet on JS!, " + new Date().toISOString())
process.exit(1)
```

#### Python

```python {"id":"01J4HK8BGKHAKYYF8G3CTSAC4T","interpreter":"/usr/bin/python3","name":"demo-py","terminalRows":"2"}
import datetime
import os

now = datetime.datetime.now()

def say_hello():
  print(" Hello world from Python, " + now.isoformat(sep='T',timespec='auto'))

say_hello()

```

```sh {"category":"exports","id":"01J4HK8BGKHAKYYF8G3DQD364S"}
echo "File name"
```

```sh {"id":"01J4HK8BGKHAKYYF8G3FTDPRT0"}
echo "New Cell Identity 0"
```
