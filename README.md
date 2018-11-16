# GitUser
#1、
git init
git add README.md
git add .
#2、
git commit -m "first commit"
3、
git remote add origin https://github.com/GSmallSea/eee.git

4、注意：要是第一次上传项目的话push之前要先git pull 一下。
git pull origin master --allow-unrelated-histories

5、
git push -u origin master
// 创建podspec 文件
6、 pod spec create WXWCategory 

7、编辑podspec文件

8、 打tag
git tag -a 0.0.1 -m"version 0.0.1”
git push --tags

9、验证
 pod lib lint --verbose
pod spec lint YJSettingTableView.podspec --verbose

10、发布
pod trunk push WXWCategory.podspec

11、更新的时候
pod cache clean --all // 清除pod缓存

