# application_docker
<br>

## 使用技術 <br>
コンテナ&nbsp;-&nbsp;web_server(PHP&Apache(php:apache)、Composer(composer:latest)、Laravel)、DB(MySQL)
<br>

## ディレクトリ構成 <br>
docker <br>
&nbsp;--&nbsp;README.md <br>
&nbsp;--&nbsp;docker-compose.yml <br>
&nbsp;--&nbsp;containers <br>
&nbsp;&nbsp;&nbsp;&nbsp;--&nbsp;web_server <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--&nbsp;Dockerfile <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--&nbsp;php.ini <br>
&nbsp;&nbsp;&nbsp;&nbsp;--&nbsp;db_mysql <br>
&nbsp;(--&nbsp;src&nbsp;&nbsp;・・・Laravelをインストールするディレクトリ) <br>
&nbsp;--&nbsp;.dockerignore <br>
<br>

## 各ファイル <br>
docker-compose.yml&nbsp;-&nbsp;コンテナたちを束ねる設定のやつ<br>
Dockerfile&nbsp;-&nbsp;コンテナを立てるための司令書 <br>
.dockerignore&nbsp;-&nbsp;`.gitignore`&nbsp;みたいなやつ <br>