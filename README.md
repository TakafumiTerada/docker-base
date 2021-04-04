# Docker Basic

## What is this ?
すぐにDocker環境を作りたい時に作れるようにするためのリポジトリ。<br>

## What is inside of repository ?
* Web
    * nginx:1.19
* App
    * php:7.4-fpm
* DB
    * mariadb:10.5
* node.js
    * node:15.13

## How to use
1.  `.env.example`を複製する
2.  複製した`.env.example`を`.env`に変更する
3.  `.env`内の`~~~_SOURCE_DIRECTORY`の値を対象のディレクトリのパスにする
4.  他に変更する箇所があれば適宜変更する
5.  Let's `docker-compose up -d --build` !!