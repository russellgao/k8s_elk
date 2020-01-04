# k8s_elk
deploy elk stack in kubernetes

## 用法
- `manifests` 已经经过测试，可以在生产环境中使用
- `experimental` 还在实验阶段

使用之前需要修改各个yaml文件的Storage，Service相关的参数，根据实际情况选择合适的介质，修改完之后执行`kubectl -f manifests` 即可。


## 包含的组件
- es
- logstash
- kibana
- kafka
- zookeeper
