# 初始化配置
git config --global user.name "user"
git config --global user.email "1938803760@qq.com"

# 检查已有配置信息
git config --list

# 初始化仓库
git init

# 将本地项目工作区文件添加到缓存区
git add .

# 提交代码说明
git commit -m "说明"

# 将本地代码仓库关联到github
git remote add origin url

# 推送到远程仓库
git push -u origin master

# 将远程仓库与本地项目同步合并
git pull --rebase origin master