# SpringBoot2.3.0の機能確認を行う

## How to build
- ビルドはMavenで実施
- mvn package

## DockerImage作成
- mvn spring-boot:build-image

## Dockerで起動
- docker run -it -p8080:8080 demo:0.0.1-SNAPSHOT

## インフラ環境確認
- http://localhost:8080/actuator/env

