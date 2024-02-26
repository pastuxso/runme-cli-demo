---
runme:
  id: 01HGZZ742BM6RYJ8ZV19GETSVX
  version: v3
  document:
    relativePath: README.md
  session:
    id: 01HQ9DSFPND9JWGAA7EFX7DTD1
    updated: 2024-02-22 17:26:28-05:00
---

# Shebang demo

#### JavaScript

```js {"id":"01HGZZ742BM6RYJ8ZV166Y3A4D","name":"demo-js","terminalRows":"2"}
console.log("Always bet on JS!, All hands demo" + new Date().toISOString())


# Ran on 2024-02-22 17:25:31-05:00 for 218ms exited with 0
Always bet on JS!, All hands demo2024-02-22T22:25:31.848Z
```

#### Python

```py {"id":"01HG7EGG30W7YJNT6C083GVANW","terminalRows":"2"}
import datetime
now = datetime.datetime.now()

def say_hello():
  print("Hello world from Python, " + now.isoformat(sep='T',timespec='auto'))

say_hello()

```
