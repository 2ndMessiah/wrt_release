致敬ZqinKing 大大打包的 ipq60xx 的包。

这个 repo 给我的 ax6600 用

# 主要修改：

## jdcloud_ipq60xx_libwrt.config
- 仅编译 jdcloud_re-cs-02，其它目标设备全部注释
- 取消AdGuard Home、自动重启、CUPSD、Docker UI、MosDNS、Samba4、SmartDNS、VLMCSD 和 Passwall的编译
- AX6600启用 zram-swap（原来是可选），新增luci-app-openclash


## update.sh
- 修改lan subnet到192.168.31.1

## release_wrt.yml
- 默认编译jdcloud_ipq60xx_libwrt

## ./patches
- 替换万吉为lucky。







