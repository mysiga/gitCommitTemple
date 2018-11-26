# git提交模板定义gitCommitTemple
### 目录
  - temples    git提交模板
  - README.md 项目说明
### 设定git提交模板
指定项目设定模板
```
git config  commit.template 模板绝对路径
```
全局设置提交模板
```
git config --global commit.template 模板绝对路径
```
如：
```
git config  commit.template /x/.simple-commit-template.txt
```
###其他
- 取消设置模板，首先通过命名打开gitconfig设置
```
vim ~/.gitconfig
```
然后把commit相关选项注释或者删除就可以了如：
```
#[commit]
#       template = ../tool/.simple-commit-template.txt
```
就可以
- 新建模板可以直接copy temples下文件，修改名字然后通过文本编译器修改内容
