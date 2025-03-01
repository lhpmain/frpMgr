[README](README.md) | [中文文档](README_zh.md)

---

### Function:

- help you to Configuration frp client 和 server.
- install frp server on the web.
- look up each server connect status.

### Install Tutorial

```shell
wget -O - https://raw.githubusercontent.com/lhpmain/OCS/master/docker/docker-all2.sh | sh
wget -O - https://raw.githubusercontent.com/lhpmain/frpMgr/master/web/src/main/docker/final/run.sh | sh
```
just run the code above on your server;

**Tip：the code just test on Debian9 CentOs7 and Ubantu18**

- **how to access**: your server ip:8999/frp 
- **default account and password**: admin/12345678
- **log information** ：1. docker ps  2. docker logs -f --tail 10 your java container ID

### How to Use:
- Resolve `*.xxx.com` to the frps server's IP. This is usually called a Wildcard DNS record.
- Configuration the server.
- install server online. 
- Configuration the client.
- run open.bat.

## Example Usage

- Resolve `*.xxx.com` to the frps server's IP
![](https://i.bmp.ovh/imgs/2019/06/b8db29874c3b85cf.png)
---
- Configuration the server.
![](https://zxx.one/imgs/2019/11/b9e77a605f309b16.png)
---
![](https://zxx.one/imgs/2019/11/537de54b7346c10b.png)
- input your remote  server's password and wait minutes .(**don't worry about your password disclosure. it just varify your server**)

- after you install and run the frp server. you can check out or restart the server 

  ```shell
  service frps status
  service frps stop
  service frps restart
  ```

  ---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Zo3i/frpMgr&type=Timeline)](https://star-history.com/#Zo3i/frpMgr&Timeline)

  
