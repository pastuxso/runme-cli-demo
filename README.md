---
runme:
  id: 01HMCJW4EBNRTNYR2XH2MQ0WV4
  version: v3
---

# I'm a README file

```sh {"id":"01HMC00FJ4JZSAHDMBSCBEWZRX","promptEnv":"auto"}
export MSG="Hello World"
export NAKED=this is a value
export USER=$( (echo $USER) )
export NAME="Cepeda"
export PWD=`pwd`

echo "$MSG $NAME!"
echo $USER

test() {
  export INNER="nested"
}

test
```

```sh {"id":"01HQBT112DNYG2G2K6E1EAAQCQ"}
echo $MSG
echo $NAKED
echo $NAME
echo $PWD
echo $INNER
```
