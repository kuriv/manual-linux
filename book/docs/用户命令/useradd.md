# useradd

执行下面的命令，创建新用户。

```
sudo useradd tom
```

执行下面的命令，创建新用户，同时自动创建家目录并指定默认 Shell 脚本。

```
sudo useradd -m -s /bin/bash tom
```

执行下面的命令，创建新用户，并添加注释。

```
sudo useradd -c "Hello World!" tom
```

