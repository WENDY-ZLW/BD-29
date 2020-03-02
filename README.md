Overview
-----
>本项目基于 Docker & Cassandra 两个软件。将 MNIST 应用部署到容器里，用户通过 curl-XPOST 命令提交带有手写体的数字图片。程序先将本图片识别出来，然后将识别的数字再返回给用户。程序对 MNIST 中用户每次提交的图片、识别的文字和时间戳信息，都会记录到 Cassandra 内进行存储。

#仓库包含内容
>>codes
>>视频演示
>>操作流程
>>Report( 项目收获，问题解决etc. )

#项目流程
* 运行mnist模型（使用tensorflow）
* 得到模型准确率，保存模型代码
* 下载并启用Dockor
* 上传图片，对图片预处理
* 得到预测结果
* 连接Cassandra检查存储

#详细步骤请参考视频！
