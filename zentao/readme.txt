zentao部署。
命令：
docker-compose up -d

默认：
使用latelee/zentao镜像。具体参考：https://hub.docker.com/r/latelee/zentao/
使用9070端口访问，最好根据实际情况修改。
挂载目录为当前目录的data（如没有会自动生成，已有则不会）。
用户名密码为admin/123456 （似乎是禅道强制如此，无法在外面修改。）
邮件使用腾讯邮箱，如果没有，不填写也没关系。但如果在实际项目中使用邮件通知功能，还是要在禅道后台设置的。