---
shell: /usr/bin/dash
skipPrompts: true
---

# Envars

```sh { name=envvar id=01HEQJD2W7NC52ZHYMRDAGY289 category=cat1 interactive=true }
$ export NEW_ENV=foo
$ echo $NEW_ENV

```

# Javascript

```javascript { name=demo-js category=cat1 closeTerminalOnSuccess=false interactive=true }
console.log("Foo Bar Baz " + new Date().toISOString())

```

# Python

```python { name=demo-python category=cat1 closeTerminalOnSuccess=false interactive=true interpreter=python3 }
def say_hello():
  print("Hello world from Python")

say_hello()

```

# Test

RunMe test:

```sh { category=cat1 interactive=false mimeType=application/geo+json }
curl -s "https://raw.githubusercontent.com/RandomFractals/vscode-data-table/main/data/world-lakes.geojson"

```
