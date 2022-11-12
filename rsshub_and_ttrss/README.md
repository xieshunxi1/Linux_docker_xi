
## Ubuntu16.04一键安装命令

sudo mkdir -p /etc/docker_xi/rsshub_and_ttrss && cd /etc/docker_xi/rsshub_and_ttrss && sudo wget  -O docker-compose.yml https://raw.githubusercontent.com/xieshunxi1/Linux_docker_xi/main/rsshub_and_ttrss/docker-compose.yml && sudo docker-compose up -d


## 安装后，一些配置

### 此配置文件是用来配Linux服务器的Rss docker-compose文件。

![image](https://user-images.githubusercontent.com/111758647/201474421-dff9b606-e56c-45ca-af15-72c67cf3b376.png)

### /mercury-parser-api 开启后，我们配置以下插件。重新进入 偏好设置 – 订阅源-插件，API 那里填 http://服务器IP:3000，然后保存即可。

![image](https://user-images.githubusercontent.com/111758647/201474372-36a12b7a-7653-4834-8d85-2211f02ffd27.png)


