# ð±ãã­ã³ãã¨ã³ãéçºãé å¼µãããäººã«åããç·´ç¿ç¨ããã¯ã¨ã³ãAPIð±

## èµ·ååã«
- dockerã¨goããä½¿ãã®PCã«ã¤ã³ã¹ãã¼ã«ãã¦ãã ãã
- env.exampleã®ååã.envã«å¤æ´ãã¦ãã ãã
- åã¨ã³ããã¤ã³ãã®è©³ç´°ã¯Swaggerã«è¨è¼ãã¦ãã¾ã

## PORT

### API

```
localhost:18080
```

### Swagger

```
localhost:18081
```

### MySQL

```
localhost:13306
```


## ã³ãã³ã

### docker èµ·å

```sh
docker-compose up -d
```

### docker åæ­¢

```sh
docker-compose down
```

### API èµ·å

```sh
go run main.go
```

---

## ä»¥ä¸ API éçºç¨ã³ã³ã½ã¼ã«

### UseCase ä½æ

```sh
node console.js u ${dirName} ${useCaseName}
```

### Repository ä½æ

```sh
node console.js r ${repositoryName}
```
# practice-api-for-frontend-beginner
