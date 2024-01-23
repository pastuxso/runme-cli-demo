---
runme:
  id: 01HGZZ742BM6RYJ8ZV19GETSVX
  version: v2.2
  document:
    relativePath: README.md
  session:
    id: 01HMVYKW2WDEZB31V6HG3GF819
    updated: 2024-01-23 15:14:00-05:00
---

# Shebang demo

#### JavaScript

```js {"id":"01HGZZ742BM6RYJ8ZV166Y3A4D","terminalRows":"2"}
console.log("Always bet on JS!, " + new Date())

```

#### Python

```python {"id":"01HG7EGG30W7YJNT6C083GVANW","terminalRows":"2"}
import datetime
now = datetime.datetime.now()

def say_hello():
  print("Hello world from Python, " + now.strftime("%Y-%m-%d %H:%M:%S"))

say_hello()


# Ran on 2024-01-23 15:02:58-05:00 for 221ms exited with 0
Hello world from Python, 2024-01-23 15:02:58
```

```sh {"id":"01HGZZ78EYK7EYPJQE7PQSGCK4"}
echo 'Hello'

```

```sh {"id":"01HGZZEK92WHGTDBNGD055T48B"}
echo "World"

```

```sh {"id":"01HGZZRJB8Q6VEJ9XKDHWNE4PJ"}
echo "From\tBash"

```
