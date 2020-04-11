Docker常见操作

```shell
//查询docker
sudo docker ps -a | grep mtosi
//进入docker容器
sudo docker exec -it pid /bin/sh
//重启docker容器
sudo docker restart pid
//往docker容器中copy,反过来也一样
sudo docker cp /home/ubuntu/xz/x.jar pid:/xz/
```



Git常见命令

git pull

git status

git log

git 