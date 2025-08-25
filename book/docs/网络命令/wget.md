# wget

执行下面的命令，下载指定单个文件。

```
wget https://codeload.github.com/kuriv/manual-linux/zip/refs/heads/master
```

执行下面的命令，通过指定的文件列表清单下载多个文件。

```
wget -i url.txt
```

执行下面的命令，下载指定单个文件并保存为其他文件名。

```
wget -O file.zip https://codeload.github.com/kuriv/manual-linux/zip/refs/heads/master
```

执行下面的命令，下载指定单个文件并保存到指定目录。

```
wget -P dir https://codeload.github.com/kuriv/manual-linux/zip/refs/heads/master
```

执行下面的命令，下载指定单个文件，同时限制下载速度。

```
wget --limit-rate=300k https://codeload.github.com/kuriv/manual-linux/zip/refs/heads/master
```

执行下面的命令，下载指定单个文件，同时打开断点续传功能。

```
wget -c https://codeload.github.com/kuriv/manual-linux/zip/refs/heads/master
```

执行下面的命令，后台下载指定单个文件。

```
wget -b https://codeload.github.com/kuriv/manual-linux/zip/refs/heads/master
tail -f wget-log
```

