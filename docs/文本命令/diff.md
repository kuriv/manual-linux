# diff

执行下面的命令，比较两个文件内容。

```
diff file1.txt file2.txt
```

执行下面的命令，比较两个文件内容，通过并排格式输出。

```
diff -y -W 50 file1.txt file2.txt
```

执行下面的命令，比较两个文件内容，通过上下文格式输出。

```
diff -c file1.txt file2.txt
```

执行下面的命令，比较两个文件内容，通过统一格式输出。

```
diff -u file1.txt file2.txt
```

执行下面的命令，生成补丁文件。

```
diff file1.txt file2.txt > file.patch
```

执行下面的命令，打补丁。

```
patch file1.txt file.patch
```

