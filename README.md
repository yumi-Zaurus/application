# application_docker

## 使用技術
コンテナ - app(PHP、Composer、Laravel)、web(Apache)、DB(MySQL)


## ディレクトリ構成
docker
 -- README.md
 -- docker-compose.yml
 -- containers
    -- app
        -- Dockerfile
        -- php.ini
    -- web
    -- db_mysql
 (-- src  ・・・Laravelをインストールするディレクトリ)
 -- .dockerignore

## 各ファイル
docker-compose.yml - コンテナたちを束ねる設定のやつ
Dockerfile - コンテナを立てるための司令書
.dockerignore - `.gitignore` みたいなやつ