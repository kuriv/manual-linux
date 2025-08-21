# paste

执行下面的命令，将两个文件按列拼接成一个新的文件。

```
paste file1.txt file2.txt
```

执行下面的命令，将多个文件按列拼接成一个新的文件。

```
paste file1.txt file2.txt file3.txt
```

执行下面的命令，将两个文件按列拼接成一个新的文件，并指定拼接符。

```
paste -d ";" file1.txt file2.txt
```

执行下面的命令，将两个文件按行拼接成一个新的文件。

```
paste -s file1.txt file2.txt
```

执行下面的命令，每行显示指定数量个文件名。

```
ls | paste -d ";" - - - -
```

