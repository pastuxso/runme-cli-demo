---
runme:
  id: 01HGZZ742BM6RYJ8ZV19GETSVX
  version: v2.2
---

# Shebang demo

#### JavaScript

```js {"id":"01HGZZ742BM6RYJ8ZV166Y3A4D","terminalRows":"2"}
console.log("Always bet on JS!, " + new Date().toISOString())

```

#### Python

```py {"id":"01HG7EGG30W7YJNT6C083GVANW","terminalRows":"2"}
import datetime
now = datetime.datetime.now()

def say_hello():
  print("Hello world from Python, " + now.isoformat(sep='T',timespec='auto'))

say_hello()

```
