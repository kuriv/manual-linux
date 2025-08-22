# join

执行下面的命令，连接两个文件内容，默认以第一列作为连接字段。

```
join file1.txt file2.txt
```

执行下面的命令，左连接两个文件内容，即显示左边文件中所有内容。

```
join -a 1 file1.txt file2.txt
```

执行下面的命令，右连接两个文件内容，即显示右边文件中所有内容。

```
join -a 2 file1.txt file2.txt
```

执行下面的命令，全连接两个文件内容。

```
join -a 1 -a 2 file1.txt file2.txt
```

执行下面的命令，连接两个文件内容，并指定输出字段。

```
join -o 1.1 1.2 1.3 2.3 file1.txt file2.txt
```

执行下面的命令，连接两个文件内容，并指定分隔符。

```
join -t $'\t' file1.txt file2.txt
```

执行下面的命令，连接两个文件内容，但只显示第一个文件中没有相同栏位的行。

```
join -v 1 file1.txt file2.txt
```

执行下面的命令，连接两个文件内容，并指定连接字段。

```
join -j 2 file1.txt file2.txt
```

