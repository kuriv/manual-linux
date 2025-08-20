# cat

执行下面的命令，查看指定文件的内容。

```
cat file.txt
```

执行下面的命令，查看多个指定文件的内容。

```
cat file1.txt file2.txt
```

执行下面的命令，查看指定文件的内容，并显示行号。

```
cat -n file.txt
```

执行下面的命令，查看指定文件的内容，并去除重复的空行。

```
cat -s file.txt
```

执行下面的命令，查看指定文件的内容，并在每行结束添加终止符。

```
cat -E file.txt
```

执行下面的命令，查看指定文件的内容，并将原文件内容重定向到新文件中。

```
cat file.txt > newfile.txt
```

执行下面的命令，查看指定文件的内容，并将原文件内容追加到新文件中。

```
cat file.txt >> newfile.txt
```

执行下面的命令，查看多个指定文件的内容，同时合并为一个新的文件。

```
cat file1.txt file2.txt > newfile.txt
```

执行下面的命令，创建新的文本文件，完成后输入 `CTRL + D` 保存文件。

```
cat > file.txt
```

