# Windows下使用Git向GitHub提交项目的操作步骤

1. 在GitHub上新建仓库

2. 在所需提交的项目的根目录中右击选择Git Bash Here

3. **第一次**用Git提交需要配置好全局选项

   ```git
   git config --global user.name "用户名"
   git config --global user.email "邮箱"
   ```

4. 初始化

   ```git
   git init
   ```

5. 把本地文件放到暂存区

   ```git
   git add .
   ```

6. 把文件放到本地仓库里面

   ```git
   git commit -m "提交信息"
   ```

7. 链接远程仓库

   ```git
   git remote add origin 链接地址（https）
   ```

8. 把本地仓库的文件推送到远程仓库

   ```git
   git push -u origin master
   ```

   回车之后等待几秒

9. 刷新GitHub仓库页面