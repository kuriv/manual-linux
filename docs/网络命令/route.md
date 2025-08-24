# route

执行下面的命令，显示当前路由。

```
route -n
```

执行下面的命令，添加或设置路由。

```
route add -net 224.0.0.0 netmask 224.0.0.0 dev ens33
```

执行下面的命令，屏蔽指定路由。

```
route add -net 224.0.0.0 netmask 224.0.0.0 reject
```

执行下面的命令，删除指定路由。

```
route del -net 224.0.0.0 netmask 224.0.0.0
route del -net 224.0.0.0 netmask 224.0.0.0 reject
```

