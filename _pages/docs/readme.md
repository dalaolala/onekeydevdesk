---
layout: page
title: docs
include_in_header: true
---


更多特点介绍和自助安装使用文档：
-------

inst.sh是一个和维护安装onekeydevdesk os镜像的脚本，也是onekeydevdesk os的recovery，类似群晖的webassiant   
ci.sh是onekeydevdesk的构建脚本，与全套的资源文件组成onekeydevdesk的codebase，可用来创建你自己的 "ddhub"

+ inst.sh
     +  [inst介绍：什么是inst.sh及它与onekeydevdesk ci.sh的关系](../../instintro/readme/)
     +  [inst使用：利用inst.sh安装onekeydevdesk，安装自定义镜像](../../instusage/readme/)
     +  [高级：对接inst.sh使用gitee,github建立你自己的镜像托管源，组装一体ddhub仓库](../../howtohost/readme/)
     +  [高级：wgetdd vs ncdd - 双机对拷和dump镜像,及简单制造打包镜像](../../ncdd/readme/)
     +  [高级：debug mode](../../debugmode/readme/)
+ ci.sh
     +  [ci介绍](../../ciintro/readme/)
     +  [ci使用：跑github actions编译inst.sh和onekeydevdesk](../../ciusage/readme/)
     +  高级和例子：扩展ci.sh，手动加入驱动,加入复杂机型网络及非DHCP支持的机型支持
          +  [azure](../../ddexpandcicustom/az/readme/)
          +  [servarica](../../ddexpandcicustom/sr/readme/)
          +  [oracle](../../ddexpandcicustom/orc/readme/)
          +  [kimsurf](../../ddexpandcicustom/ks/readme/)
          +  [bwg10g512m](../../ddexpandcicustom/bwglowres/readme/)
+  onekeydevdesk
     +  [什么是onekeydevdesk os](../../devdeskintro/readme/)
     +  [设置onekeydevdesk](../../devdeskusage/readme/)
     +  [设置和使用云黑群镜像]
     +  [设置和使用deepin](../../dpiusage/readme/)
     +  [设置和使用cloudrevebox](../../cloudreveboxusage/readme/)
     +  [直接把pve面板当web面板和探针面板]
     +  [todo高级：使用openwrt容器打造云软路由]
     +  [todo高级：使用osx/win打造本地mac/win的mateos桌面]
     +  [todo高级：利用onekeydevdesk中的pve封装制造硬盘镜像]
     +  [todo高级：利用onekeydevdesk汇聚闲置机打造你的个人IDC]
