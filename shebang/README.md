---
runme:
  id: 01HGZZ742BM6RYJ8ZV19GETSVX
  version: v3
---

# Shebang demo

```sh {"id":"01HS1Z2VGNR2XH04TPGKPT8ZH8"}
which runme
which go
```

```sh {"id":"01HRCNG3ZXPY76J98HEQ4JV4AR","interactive":"true","name":"export-vars","promptEnv":"auto","terminalRows":"3"}
export DOG_NAME="Roscoe"
export FOO_BAR="BAZ LOO"
export NAKED="naked"
export NEW_VAR="Here is a new var"
export NEW_VAR2="new var 2"
echo "Foo"
```

#### JavaScript

```js {"name":"demo-js","terminalRows":"2"}
console.log("Always bet on JS!, " + new Date().toISOString())
process.exit(1)
```

#### Python

```python {"id":"01HG7EGG30W7YJNT6C083GVANW","interpreter":"/usr/bin/python","name":"demo-py","terminalRows":"2"}
import datetime
import os

now = datetime.datetime.now()

def say_hello():
  print(" Hello world from Python, " + now.isoformat(sep='T',timespec='auto'))

say_hello()

```

```sh
echo "File name"
```

```sh
echo "New Cell"
```
