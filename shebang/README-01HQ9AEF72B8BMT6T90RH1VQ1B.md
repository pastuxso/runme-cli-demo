---
runme:
  id: 01HGZZ742BM6RYJ8ZV19GETSVX
  version: v3
  document:
    relativePath: README.md
  session:
    id: 01HQ9AEF72B8BMT6T90RH1VQ1B
    updated: 2024-02-22 16:10:54-05:00
---

# Shebang demo

#### JavaScript

```js {"id":"01HGZZ742BM6RYJ8ZV166Y3A4D","name":"demo-js","terminalRows":"2"}
console.log("Always bet on JS!, All hands demo" + new Date().toISOString())

```

#### Python

```py {"id":"01HG7EGG30W7YJNT6C083GVANW","terminalRows":"2"}
import datetime
now = datetime.datetime.now()

def say_hello():
  print("Hello world from Python, " + now.isoformat(sep='T',timespec='auto'))

say_hello()


# Ran on 2024-02-22 16:09:57-05:00 for 278ms exited with 0
Hello world from Python, 2024-02-22T16:09:57.680119
```
