# docker-jenkins-slave-electron

[`seachicken/docker-jenkins-slave-electron`](https://hub.docker.com/r/seachicken/docker-jenkins-slave-electron/)

Electronビルド環境のJenkinsスレーブコンテナです。

Jenkinsのマスターノードをコンテナ管理している場合にリンクさせて使用できます。  
尚、マスターとスレーブのコンテナが同一ホスト上にある場合も動作します。

## Running
To run a Docker container
```sh
docker run -itd --link <master container name>:master seachicken/docker-jenkins-slave-electron <secret> <slave name>
```
