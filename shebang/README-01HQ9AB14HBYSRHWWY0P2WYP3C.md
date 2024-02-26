---
runme:
  id: 01HGZZ742BM6RYJ8ZV19GETSVX
  version: v3
  document:
    relativePath: README.md
  session:
    id: 01HQ9AB14HBYSRHWWY0P2WYP3C
    updated: 2024-02-22 16:09:51-05:00
---

# Shebang demo

#### JavaScript

```js {"id":"01HGZZ742BM6RYJ8ZV166Y3A4D","name":"demo-js","terminalRows":"2"}
console.log("Always bet on JS!, All hands demo" + new Date().toISOString())


# Ran on 2024-02-22 16:09:27-05:00 for 317ms exited with 0
Always bet on JS!, All hands demo2024-02-22T21:09:28.054Z
```

#### Python

```py {"id":"01HG7EGG30W7YJNT6C083GVANW","terminalRows":"2"}
import datetime
now = datetime.datetime.now()

def say_hello():
  print("Hello world from Python, " + now.isoformat(sep='T',timespec='auto'))

say_hello()


# Ran on 2024-02-22 16:09:17-05:00 for 276ms exited with 0
Hello world from Python, 2024-02-22T16:09:17.329131
```
