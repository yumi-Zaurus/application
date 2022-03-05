# application_docker
<br>

## 使用技術 <br>
コンテナ&nbsp;-&nbsp;app(PHP(php:latest)、Composer(composer:latest)、Laravel)、web(Apache(httpd:latest))、DB(MySQL)
<br>

## ディレクトリ構成 <br>
docker <br>
&nbsp;--&nbsp;README.md <br>
&nbsp;--&nbsp;docker-compose.yml <br>
&nbsp;--&nbsp;containers <br>
&nbsp;&nbsp;&nbsp;&nbsp;--&nbsp;app <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--&nbsp;Dockerfile <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;--&nbsp;php.ini <br>
&nbsp;&nbsp;&nbsp;&nbsp;--&nbsp;web <br>
&nbsp;&nbsp;&nbsp;&nbsp;--&nbsp;db_mysql <br>
&nbsp;(--&nbsp;src&nbsp;&nbsp;・・・Laravelをインストールするディレクトリ) <br>
&nbsp;--&nbsp;.dockerignore <br>
<br>

## 各ファイル <br>
docker-compose.yml&nbsp;-&nbsp;コンテナたちを束ねる設定のやつ<br>
Dockerfile&nbsp;-&nbsp;コンテナを立てるための司令書 <br>
.dockerignore&nbsp;-&nbsp;`.gitignore`&nbsp;みたいなやつ <br>