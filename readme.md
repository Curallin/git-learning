## 1. 检查当前 Git 配置

```
git config --list
```

你会看到类似：

```
user.name=yourname
user.email=youremail@example.com
```

------

## 2. 设置全局配置（可选）

如果你平时主要用某一个账号，可以先配置全局信息：

```
git config --global user.name "你的用户名"
git config --global user.email "你的邮箱"
```

⚠️ 这个配置会影响 **所有仓库**。

------

## 3. 针对单个仓库设置不同账号

进入你某个仓库的文件夹，运行：

```
cd your-repo
git config user.name "另一个用户名"
git config user.email "另一个邮箱"
```

这样只会对 **当前仓库** 生效，不会影响其他仓库。