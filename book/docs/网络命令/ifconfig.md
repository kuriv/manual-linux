# ifconfig

执行下面的命令，显示网络设备信息。

```
ifconfig
```

执行下面的命令，关闭指定网卡。

```
sudo ifconfig eth0 down
```

执行下面的命令，开启指定网卡。

```
sudo ifconfig eth0 up
```

执行下面的命令，为指定网卡配置指定 IP 地址和子网掩码。

```
sudo ifconfig eth0 192.168.10.233 netmask 255.255.255.0
```

执行下面的命令，修改指定网卡的 MAC 地址。

```
sudo ifconfig eth0 down
sudo ifconfig eth0 hw ether 00:AA:BB:CC:DD:EE
sudo ifconfig eth0 up
```

执行下面的命令，关闭指定网卡的 ARP 协议。

```
sudo ifconfig eth0 arp
```

执行下面的命令，开启指定网卡的 ARP 协议。

```
sudo ifconfig eth0 -arp
```

执行下面的命令，设置指定网卡的最大传输单元。

```
sudo ifconfig eth0 mtu 1500
```

