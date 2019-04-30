### github使用（备忘）

1. 在github里配置SSH密钥，方式为在Git Bash Here 命令行中输入ssh-keygen -t rsa -C "your_email@youremail.com"
2. 一路默认生成后的密钥在github的setting中配置好，再在命令行中输入   ssh -T git@github.com   如果是第一次的会提示是否continue，输入yes就会看到：You've successfully authenticated, but GitHub does not provide shell access 。这就表示已成功连上github。
3. 仓库啥的可以在github官网创建
4. 使用 git clone 命令克隆下仓库目录，然后 cd 进入目录中，使用命令 git add .  添加所有新增的文件
5. git commit -m "提交信息"  添加提交时的备注信息
6. git push -u origin master 推送至github上 第一次提交需要验证用户名和密码，非第一次可以 git push origin master