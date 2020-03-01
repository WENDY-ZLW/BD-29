Overview
  本项目基于 Docker & Cassandra 两个软件。将 MNIST 应用部署到容器里，用户通 过 curl -XPOST 命令提交带有手写体的数字图片。程序先将本图片识别出来，然后将识别 的数字再返回给用户。程序对 MNIST 中用户每次提交的图片、识别的文字和时间戳信息， 都会记录到 Cassandra 内进行存储。
