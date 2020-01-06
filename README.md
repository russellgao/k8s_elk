# k8s_elk
deploy elk stack in kubernetes

## Usage
- `manifests` Can run in production environment
- `experimental` In the experimental stage

使用之前需要修改各个yaml文件的Storage，Service相关的参数，根据实际情况选择合适的介质，修改完之后执行`kubectl -f manifests` 即可。


## Component
- es
- logstash
- kibana
- kafka
- zookeeper


## More
- [https://mp.weixin.qq.com/s/93_Jf8P69Q0nkw1Ip7MsFQ](https://mp.weixin.qq.com/s/93_Jf8P69Q0nkw1Ip7MsFQ)
