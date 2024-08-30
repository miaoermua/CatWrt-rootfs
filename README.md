# CatWrt-rootfs

适用于 Docker 版的 CatWrt，和普通固件使用上可能有差别

<https://www.miaoer.xyz/posts/network/1panel-deploy-catwrt-rootfs>

```
$ wget https://service.miaoer.xyz/CatWrt-rootfs/docker-compose.yml
# wget -P  /opt/1panel/docker/compose/CatWrt/ https://service.miaoer.xyz/CatWrt-rootfs/docker-compose.yml

$ docker compose up -d
```

## 软件源

适用于本地 CatWrt 的软件源，本地部署可减少依赖在线服务

```
$ wget https://fastly.jsdelivr.net/gh/miaoermua/CatWrt@main/docker-compose.yml

$ docker compose up -d
```
