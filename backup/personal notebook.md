
# 代码笔记测试：git的一些指令笔记
# 🚀 Git 使用指令大全

## 📌 基础操作
```bash
git init                     # 初始化仓库
git clone <repository_url>   # 克隆远程仓库
git status                   # 查看仓库状态
git add <file>               # 添加文件到暂存区
git add .                    # 添加当前目录所有文件
git commit -m "信息"          # 提交
git commit --amend -m "新信息" # 修改最后一次提交信息
git log                      # 查看提交历史
git log --oneline            # 简洁日志
git log --graph --all --decorate   # 图形化日志
## 分支管理
git branch                        # 查看分支
git branch <branch>               # 创建分支
git checkout <branch>             # 切换分支
git switch <branch>               # 新推荐写法
git checkout -b <branch>          # 创建并切换分支
git switch -c <branch>            # 新推荐写法
git branch -d <branch>            # 删除已合并分支
git branch -D <branch>            # 强制删除
git branch -m <old> <new>         # 重命名分支

