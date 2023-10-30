查看 `docker` 占用磁盘空间

`docker system df -v`

---

清理 `docker` 构建缓存 `build cache`

`docker builder prune`

---

备份数据卷 `volume`

https://docs.docker.com/storage/volumes/#back-up-restore-or-migrate-data-volumes

---

挂载匿名卷

`docker run -v /dbdata`

---

挂载命名卷

`docker run -v dbdata:/dbdata`

---

使用 `docker run --rm -v /data` 挂载的匿名卷会在删除容器之后自动删除

https://docs.docker.com/storage/volumes/#remove-anonymous-volumes

---

删除全部未使用的数据卷

`docker volume prune`

---

删除容器的时候显式删除挂载卷

`docker rm -v`

---

显示容器使用的系统资源

`docker stats`
