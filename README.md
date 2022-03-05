# application_docker
<br>

## 使用技術 <br>
コンテナ - app(PHP、Composer、Laravel)、web(Apache)、DB(MySQL)
<br>

## ディレクトリ構成 <br>
docker <br>
 -- README.md <br>
 -- docker-compose.yml <br>
 -- containers <br>
    -- app <br>
        -- Dockerfile <br>
        -- php.ini <br>
    -- web <br>
    -- db_mysql <br>
 (-- src  ・・・Laravelをインストールするディレクトリ) <br>
 -- .dockerignore <br>
<br>

## 各ファイル <br>
docker-compose.yml - コンテナたちを束ねる設定のやつ<br>
Dockerfile - コンテナを立てるための司令書 <br>
.dockerignore - `.gitignore` みたいなやつ <br>