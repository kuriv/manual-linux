# curl

执行下面的命令，获取指定网站的网页源码。

```
curl www.google.com
```

执行下面的命令，获取指定网站的网页源码并保存。

```
curl -o google.html www.google.com
```

执行下面的命令，下载指定单个文件。

```
curl -O https://codeload.github.com/kuriv/manual-linux/zip/refs/heads/master
```

执行下面的命令，下载指定单个文件并保存为其他文件名。

```
curl -o file.zip https://codeload.github.com/kuriv/manual-linux/zip/refs/heads/master
```

执行下面的命令，下载指定单个文件，同时打开断点续传功能。

```
curl -C - -O https://codeload.github.com/kuriv/manual-linux/zip/refs/heads/master
```

执行下面的命令，获取指定网站的 HTTP 响应头信息。

```
curl -I www.google.com
```

