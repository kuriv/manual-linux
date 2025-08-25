# touch

执行下面的命令，创建新的空白文件。

```
touch file.txt
```

执行下面的命令，依次创建多个新的空白文件。

```
touch file1.txt file2.txt file3.txt
```

执行下面的命令，更新已有文件的访问时间戳。

```
touch -a file.txt
```

执行下面的命令，更新已有文件的修改时间戳。

```
touch -m file.txt
```

执行下面的命令，更新已有文件的时间戳而不创建新的空白文件。

```
touch -c nofile.txt
```

执行下面的命令，将访问时间戳和修改时间戳从一个文件复制到另一个文件。

```
touch file1.txt -r file2.txt
```

执行下面的命令，更新已有文件的访问时间戳和修改时间戳为明天。

```
touch -d "tomorrow" file.txt
```

执行下面的命令，更新已有文件的访问时间戳和修改时间戳为指定时间。

```
touch -t 2001010000.00 file.txt
```

