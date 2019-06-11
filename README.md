Node Setup
==============

### Decrypt

```shell
git-crypt unlock
tar zxvf content.tar.gz

```

### Encrypt

```shell
tar czvf content.tar.gz content
gpg-crypt lock -a
```

> Freedom is not free.
