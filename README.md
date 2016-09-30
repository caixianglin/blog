### 部署步骤
```
hexo clean  #清除public目录
hexo generate
hexo deploy
#简写
hexo n == hexo new
hexo g == hexo generate
hexo s == hexo server
hexo d == hexo deploy
```
### 一些常用命令
```
hexo new "postName" #新建文章
hexo new page "pageName" #新建页面
hexo generate #生成静态页面至public目录
hexo server #开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
hexo deploy #将.deploy目录部署到GitHub
hexo help  # 查看帮助
hexo version  #查看Hexo的版本
```
### 基本路径
  文章在source/_posts，如果想修改头像可以直接在主题的_config.yml文件里面修改，友情链接，之类的都在这里，修改名字在public/index.html里修改。
  public目录存放生成的文件，deploy存放上传git的文件。