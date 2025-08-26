# tr

执行下面的命令，将指定文件中的小写字母转换为大写字母。

```
tr [a-z] [A-Z] < file.txt
cat file.txt | tr [:lower:] [:upper:]
```

执行下面的命令，删除指定字符串中的小写字母。

```
echo "abcABCdefDEF" | tr -d [a-z]
```

执行下面的命令，删除指定字符串中的数字。

```
echo "abc123def456" | tr -d [0-9]
```

执行下面的命令，删除制定字符串中的空格与制表符。

```
echo "	Hello World!" | tr -d [ \t]
```

