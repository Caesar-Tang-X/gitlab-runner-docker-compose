# GiaLab-Runner Docker Compose YML File


## 简介
    docker 一键启动 GiaLab-Runner 容器的 docker-compose.yml 配置


## 镜像环境：
	gitlab/gitlab-runner:v15.11.1


## 导入镜像：
	docker load -i 镜像包


## 启动命令：
	docker-compose up -d


## 安装及生成数据路径：
    ├── mysql 
        ├── images                      镜像文件文件目录
        ├── gitlab-runner               容器挂载目录
            └── config                  	配置文件目录
        ├── docker-compose.yml          docker-compose.yml
        └── README.md                   README.md