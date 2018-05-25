# LAMP環境構築
Dockerを使用したPHPの開発環境(LAMP)を構築

## ツール
* Docker for Windows (or Max)
* Docker ToolBox

## 使用したイメージ
* php:7.1.17-apache [(OFFICIAL)](https://hub.docker.com/_/php/)
* mysql:5.7 [(OFFICIAL)](https://hub.docker.com/_/mysql/)
* busybox:latest [(OFFICIAL)](https://hub.docker.com/_/busybox/)

## 環境情報
* PHP    7.1.17
* Apache 2.4.10
* MySQL  5.7.22

## 使用方法
```
1. git clone https://github.com/KazuhisaFukuda/docker-lamp.git
2. cd docker-lamp
3. docker-compose up -d
```
## PHPINFO
| docker for windows (or mac) | http://localhost |
|:-----------|:-----------|
| docker toolbox | http://192.168.99.100 |
