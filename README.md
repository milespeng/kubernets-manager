# kubernets-manager
kubernets-manager via  fastapi ; vue

# 功能
1、现有Kubernet集群 描述
    namespace
        - 资源调度
    service
        - 变更
        - 修改label，name
    deployment
        - label
        - pod list
    pod
        - exec
        - log
        - describe
        - kill
        - restart
    configmap
        - add
        - update
        - delete

2、从git处获得 yaml/json文件，解析k8s结构，列出与线上版本的差异，执行变更操作
3、调整当前环境，生成yaml文件
4、监控页面
5、日志处理
6、权限管理
7、操作/变更历史查询
