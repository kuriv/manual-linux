# egrep

执行下面的命令，查找指定文件中包含一个或以上关键字的内容。

```
egrep 'He+' file.txt
```

执行下面的命令，查找指定文件中包含不同关键字的内容。

```
egrep 'Hello|World!' file.txt
```

执行下面的命令，查找指定文件中包含整体关键字的内容。

```
egrep '(Hello)' file.txt
```

执行下面的命令，查找指定文件中包含一个或以上整体关键字的内容。

```
egrep '(Hello)+' file.txt
```

执行下面的命令，查找指定文件中包含两次整体关键字的内容。

```
egrep '(Hello){2}' file.txt
```

执行下面的命令，查找指定文件中以关键字开头的内容。

```
egrep '^H' file.txt
```

执行下面的命令，查找指定文件中以关键字结尾的内容。

```
egrep '!$' file.txt
```

执行下面的命令，查找指定文件中包含可选关键字的内容。

```
egrep '[hH]ello' file.txt
```

