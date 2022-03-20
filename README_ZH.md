# ipio

[🇬🇧 English](README.md)

[🗣 News](https://t.me/txthinking_news)
[💬 Chat](https://join.txthinking.com)
[🩸 Youtube](https://www.youtube.com/txthinking) 
[❤️ Sponsor](https://github.com/sponsors/txthinking)

👉 **全局代理** 👈 : tun2brooklink, tun2socks5. IPv4 and IPv6, TCP and UDP.

A project by [txthinking.com](https://www.txthinking.com)

### 通过 [nami](https://github.com/txthinking/nami) 安装

```
nami install ipio
```

### 使用

**需要ROOT/Admin权限**

### tun2brooklink

```
ipio tun2brooklink -l 'brook://server.wsserver.wssserver.socks5...' --fakeDNS
```

自定义DNS，分流，路由，等等：`ipio tun2brooklink -h`

### tun2socks5

假设你的 socks5 server is `1.2.3.4:1080`. **你的socks5必须支持标准 UDP 协议, 推荐 [brook](https://github.com/txthinking/brook) socks5**

```
ipio tun2socks5 -s 1.2.3.4:1080 --fakeDNS
```

自定义DNS，分流，路由，等等：`ipio tun2socks5 -h`

## 协议

基于 GPLv3 协议
