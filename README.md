# 克隆您的仓库（将URL替换为您的仓库URL）
git clone https://github.com/your-username/OsMapApp.git
cd OsMapApp# 假设解压文件在/mnt/data/OsMapApp目录下
cp -r /mnt/data/OsMapApp/* .

# 初始化Git仓库（如果尚未初始化）
git init

# 添加所有文件并提交
git add .
git commit -m "Initial commit with Ionic project files"
git push origin main
