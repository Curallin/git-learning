1. 确保配置密钥完成配对并连接成功

2. 在github上创建项目仓库

   ![image-20250819123545594](C:\Users\sysum\AppData\Roaming\Typora\typora-user-images\image-20250819123545594.png)

3. 使用curallin这个用户来上传本地文档

4. 步骤

   1. 切换到上传的文档根目录，终端使用`git init`初始化项目

   2. 配置用户名和邮箱

      ```cmd
      git config user.name "curallin"
      git config user.email "SYSUcurallin@outlook.com"
      ```

   3. 重命名当前分支并且给本地仓库添加一个远程仓库地址

      ```cmd
      git branch -M main
      git remote set-url origin git@curallin:Curallin/git-learning.git 
      ```

   4. 推送到远程仓库

      ```
      git push -u origin main
      ```

      