# syno-acme
通过acme协议更新群晖HTTPS泛域名证书的自动脚本

使用方法参见: [http://www.up4dev.com/2018/05/29/synology-ssl-wildcard-cert-update/](http://www.up4dev.com/2018/05/29/synology-ssl-wildcard-cert-update/)


## Edited by Carl 20240324
为了适应acme.sh的更新，将原先固定从`https://cdn.jsdelivr.net/gh/andyzhshg/syno-acme@master/acme.sh.address`获取脚本包的方法，改为了手动配置
修改 acme.sh.address 中的地址即可改变版本


使用前，修改 config，填写域名，账户邮箱，认证 API，等信息
更换 acme.sh 版本，修改 acme.sh.address 【acme.sh.address 仅能输入单行URL地址，否则报错】