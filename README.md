# MyAdBlockRules
我个人用到的一些广告拦截规则

## 关于p2pcdnblock.txt

现在APP已经开始有内置httpdns(域名/直连IP两种形式)，直连IP等方式用于解决域名被拦截的问题，dns拦截方案逐渐进入失效阶段，后续如果需要拦截可能要MITM或者其他拦截方案，建议采用[pcdn-detector](https://github.com/Womsxd/pcdn-detector)作为PCDN拦截方案，pcdn-detector需要在路由器上运行，openwrt插件[luci-app-pcdn-detector](https://github.com/Womsxd/luci-app-pcdn-detector)
