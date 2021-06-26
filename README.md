# rabbitmq

1. pull image

   ```shell
   docker pull rabbitmq:3.8.17-management
   ```

   

2. git clone

   ```shell
   git clone https://github.com/fangxh2013/rabbitmq-docker-compose.git
   ```

   

3. 进入目录，运行命令启动rabbitmq：

```shell
docker-compose up -d
```



4. 浏览器中输入以下url进入管理界面：

   ```shell
   http://localhost:15672/
   ```

   

5.输入账号密码（在docker-compose.yml中设置）：

账号：`rabbitmq`

密码：`rabbitmq`

![](/Users/felix/Desktop/截屏2021-06-26 下午3.47.51.png)
