# Hp1020-laserJet-1020 printer

打印机地址：（一般不会改变，尽量不要关闭服务器，服务器在李继工位下面）
http://172.25.19.163:631/printers/HP-LaserJet-1020

安装步骤：
1. ![printer](https://raw.githubusercontent.com/Purerli/image/main/printer/printer.4u0lap0zj480.webp)
2. ![printer](https://raw.githubusercontent.com/Purerli/image/main/printer/printer.5pnx2h6zv8w0.webp)
3. ![2767a57bb0365261d39f849d6a63c1b](https://raw.githubusercontent.com/Purerli/image/main/printer/2767a57bb0365261d39f849d6a63c1b.6r5d8m0tqm40.webp)
4. ![15827329ce82d45409126266a2969dc](https://raw.githubusercontent.com/Purerli/image/main/printer/15827329ce82d45409126266a2969dc.1234l8viwgmo.webp)
5. ![6bb286ba1d0891c7ab431bf5dc1a655](https://raw.githubusercontent.com/Purerli/image/main/printer/6bb286ba1d0891c7ab431bf5dc1a655.53ukib162b80.webp)

驱动地址：
在本仓库的driver里面


常见问题：
1. ip变了，尝试ping一下172.25.19.163这个地址，如果ip变了。原因有俩：1.服务器重启，2.服务器关机
2. 服务端驱动损坏。修复过程：ssh b1023@172.25.19.163，密码私聊问我，登录上之后有一个driver文件夹,复制执行./hplip-3.21.10.run（已给权限，该账户没有管理员权限），等待安装完成，再次尝试打印