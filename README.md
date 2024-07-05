# Starter REST Api

This is an example REST Api designed to be deployed on Cyclic.sh




## Examples

### Create/Update - Insert/Upsert

```shell
curl -i https://localhost:3000/animals/rin%20tin%20tin \
    --data '{"breed":"German Shepard", "gender": "male"}' \
    -XPOST -H 'Content-Type: application/json'
```

### Read All - List

```shell
curl -i https://localhost:3000/animals
```

### Read

```shell
curl -i https://localhost:3000/animals/lassy
```

### Delete

```shell
curl -i -XDELETE https://localhost:3000/animals/lassy
```
