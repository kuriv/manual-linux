# mv

执行下面的命令，将文件移动到新目录中。

```
mv file.txt dir
```

执行下面的命令，将文件重命名。

```
mv file.txt newfile.txt
```

执行下面的命令，将文件重命名，若新文件已存在，则询问是否覆盖。

```
mv -i file.txt newfile.txt
```

执行下面的命令，将文件重命名，若新文件已存在，则直接覆盖。

```
mv -f file.txt newfile.txt
```

执行下面的命令，在文件被覆盖之前备份。

```
mv -b file.txt newfile.txt
```

执行下面的命令，仅当源文件比目标文件新时，才执行更新操作。

```
mv -u file.txt newfile.txt
```

执行下面的命令，将一个目录移动到另一个目录中。

```
mv dir1 dir2
```

执行下面的命令，将当前目录下所有文件移动到上级目录。

```
mv * ..
```

