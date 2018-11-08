Node Setup
==============

### Write

```shell
tar czf content.tar.gz content
gpg --encrypt --armor --recipient guyifan1121@gmail.com content.tar.gz

```

### Read

```shell
gpg --decrypt content.tar.gz.asc > content.tar.gz
tar zxvf content.tar.gz
```

> Freedom is not free.
