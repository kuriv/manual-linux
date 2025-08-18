# rename

执行下面的命令，以字符串替换方式修改文件扩展名。

```
rename 's/.txt/.doc/' file.txt
```

执行下面的命令，以字符串替换方式模拟批量修改文件名。

```
rename -n 's/file/file0/' file*
```

执行下面的命令，以字符串替换方式批量修改文件名，并显示执行过程信息。

```
rename -v 's/file/file0/' file*
```

