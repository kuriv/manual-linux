# useradd

执行下面的命令，创建新用户。

```
sudo useradd tom
```

执行下面的命令，创建新用户，同时指定家目录和默认 Shell 脚本。

```
sudo useradd -m -s /bin/bash tom
```

执行下面的命令，创建新用户，并添加注释。

```
sudo useradd -c "Hello World!" tom
```

