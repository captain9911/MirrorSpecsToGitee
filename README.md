# 关于

这个 Action 会每天自动将 <a href="https://github.com/CocoaPods/Specs">CocoaPods/Specs</a> 仓库镜像至 Gitee。

镜像地址为：https://gitee.com/captain9911/DCSpecs.git

# 使用
将CocoaPods索引更换成镜像：

```
rm -rf ~/.cocoapods/repos
pod repo add DCSpecs https://gitee.com/captain9911/DCSpecs.git
```

以后更新本地索引时，就会直接从镜像拉取，速度飞快。

```
pod repo update
```
