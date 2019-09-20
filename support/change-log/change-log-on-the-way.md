Kuboard v1.0.x 的更新说明

## v1.0.3-beta.6

**发布日期**

2019年9月19日

**BUG 修复**

* 预览的 YAML 不能第二次使用 kubectl apply 的问题（YAML 中存在空 MAP）







* terminationGracePeriodSeconds
* Service --> SessionAffinity
              --> clientIP.timeoutSeconds
* Service --> .spec.clusterIP
* --privileged
* mountPropagation

* 创建工作负载时，不追加前缀
* 存储卷声明去掉分配模式的字段
* 删除容器组时 - graceful period
* Pod Conditions: lastProbeTime/reason/message
* 按名称空间查看 Events
* 显示 Deployment/StatefulSet/DaemonSet 的事件
* 控制台/日志界面，按 名称空间/工作负载/Pod/容器 进行切换
* hostPort
* StatefulSet 在 available 数与 replicas 数不一致时，链接到帮助提示