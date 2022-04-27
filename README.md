编译方法:

* 1.去官网下载一份sdk并解压

* 2.cd sdk

* 3.git clone https://github.com/AutoCONFIG/minieap-openwrt.git package/minieap-openwrt

* 4.make menuconfig

* 5.make package/minieap-openwrt/compile

仓库说明：
main为默认分支，不带有任何的脚本，编译后的ipk仅包含minieap本体程序
no scripts表示不带有执行脚本
