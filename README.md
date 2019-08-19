# spring-boot-deploy
  支持spring boot生成的可以执行jar多节点部署
  
# 脚本运行环境

## 本地环境
  - python3
  - 安装paramko库
  
## 服务器环境
  - linux
  - jre
  - ssh支持
  
# 部署
```python
  python deploy-jar.py deploy_path remote_dir jar_name
```
例如要发布程序为service-admin.1.0.0.jar,
发布的本地路径为C:\service\service-admin,
服务器远程路径为/service/service-admin
发布脚本为  python deploy-jar.py C:\service\service-admin /service/service-admin service-admin.1.0.0.jar

# 参考文档
  [使用python脚本进行SpringBoot项目多节点上传部署](https://www.jianshu.com/p/74979fbdb103)
  
  
  
