---
runme:
  id: 01HGZZ742BM6RYJ8ZV19GETSVX
  version: v3
  document:
    relativePath: README.md
  session:
    id: 01HQBSQK607QV01TVE1DRANQXQ
    updated: 2024-02-23 15:21:20-05:00
---

# Shebang demo

#### JavaScript

```js {"id":"01HGZZ742BM6RYJ8ZV166Y3A4D","name":"demo-js","terminalRows":"2"}
console.log("Always bet on JS!, All hands demo" + new Date().toISOString())


# Ran on 2024-02-23 15:16:18-05:00 for 287ms exited with 0
Always bet on JS!, All hands demo2024-02-23T20:16:18.569Z
```

#### Python

```py {"id":"01HG7EGG30W7YJNT6C083GVANW","terminalRows":"2"}
import datetime
now = datetime.datetime.now()

def say_hello():
  print("Hello world from Python, " + now.isoformat(sep='T',timespec='auto'))

say_hello()


# Ran on 2024-02-23 15:15:44-05:00 for 287ms exited with 0
Hello world from Python, 2024-02-23T15:15:44.856178
```
