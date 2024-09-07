# openwrt-package
openwrt补充包

如果想要在feeds.conf.default中添加单个包的话，由于feeds的管理方式（feeds中的每个包单独存在一个文件夹），会报错（目标模式不含有“%”。 停止。），所以需要一个仓库来单独放置各个包的内容。