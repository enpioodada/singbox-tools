#  使用方法
## 1. 导入内核到 Linux 端
**sing-box 内核下载链接后缀和 CPU 架构对应关系如下表：**
|CPU 架构|AMD64|AMD64v3|ARMv5|ARMv6|ARMv7|ARMv8&ARM64&AArch64|mips-softfloat|mipsle-hardfloat|mipsle-softfloat|
|-----|-----|-----|-----|-----|-----|:---:|-----|-----|-----|
|**链接后缀**|`amd64`|`amd64v3`|`armv5`|`armv6`|`armv7`|`armv8`|`mips-softfloat`|`mipsle-hardfloat`|`mipsle-softfloat`|
```
# sing-box 内核 PuerNya 版
curl -L https://github.com/enpioodada/singbox-tools/raw/main/sing-box-puernya/sing-box-linux-amd64v3.tar.gz | tar -zx -C /usr/local/bin
```
## 2. 安装 Clash dashboard 面板
**Clash dashboard 面板对应文件名和在线地址关系如下表：**
|面板类型|文件名|在线地址|
|-----|-----|-----|
|Clash 官方面板|`clash-dashboard.tar.gz`|https://clash.razord.top|
|Razord-meta 面板|`Razord-meta.tar.gz`|https://clash.metacubex.one|
|yacd 面板|`yacd.tar.gz`|https://yacd.haishan.me|
|Yacd-meta 面板|`Yacd-meta.tar.gz`|https://yacd.metacubex.one|
|metacubexd 面板|`metacubexd.tar.gz`|https://metacubex.github.io/metacubexd|

metacubexd面板执行如下命令：
```
curl -L https://raw.githubusercontent.com/enpioodada/singbox-tools/main/Clash-dashboard/metacubexd.tar.gz | tar -zx -C /usr/local/sing-box/ui
```

Yacd-meta面板执行如下命令：
```
curl -L https://raw.githubusercontent.com/enpioodada/singbox-tools/main/Clash-dashboard/Yacd-meta.tar.gz | tar -zx -C /usr/local/sing-box/ui
```
