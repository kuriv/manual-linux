# grep

执行下面的命令，搜索指定文件中包含某个关键词的内容。

```
grep kuriv /etc/passwd
```

执行下面的命令，搜索多个文件中包含某个关键词的内容。

```
sudo grep kuriv /etc/passwd /etc/shadow
```

执行下面的命令，搜索多个文件中包含某个关键词的内容，但不显示文件名。

```
sudo grep -h kuriv /etc/passwd /etc/shadow
```

执行下面的命令，搜索多个文件中包含某个关键词的内容，并统计出现次数。

```
sudo grep -c kuriv /etc/passwd /etc/shadow
```

执行下面的命令，搜索指定文件中包含某个关键词的内容，并忽略大小写。

```
grep -i KURIV /etc/passwd
```

执行下面的命令，搜索指定文件中包含某个关键词的内容，并显示行号。

```
grep -n kuriv /etc/passwd
```

执行下面的命令，反向查找指定文件，即指定文件中不包含某个关键词的内容。

```
grep -v kuriv /etc/passwd
```

执行下面的命令，搜索指定文件中精准匹配到某个关键词的内容。

```
grep -x Hello file.txt
```

执行下面的命令，只搜索包含某个关键词内容的文件名，但不列出具体的匹配行。

```
grep -l Hello *
```

执行下面的命令，递归搜索当前目录下所有文件中包含某个关键词的内容。

```
grep -rl Hello *
```

执行下面的命令，判断指定文件中是否包含某个关键词的内容，通过返回状态值输出结果。

```
grep -q kuriv /etc/passwd
echo $?
```

