# k8s-prometheus


1. 首先安装prometheus相关的yaml，安装顺便为configmap.yaml、rbac.yaml、rules.yaml、statefulset.yaml、service.yaml。 prometheus-rules.yaml用来定义prometheus的监控策略。

2. node_exporter.sh为node监控所需要脚本

3. kube-state-metrics 使用来监控k8s平台的组件状态情况

4. alertmanager用来配合prometheus来进行发送告警的，alertmanager-configmap用来给alertmanager提供配置参数.
