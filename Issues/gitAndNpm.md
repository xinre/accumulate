#### 1. 常用git命令

- git remote -v  查看所有远端信息
- git remote add 库的名称 库的url		增加一个远端
- git add . 提交到缓存区
- git commit -m ‘…..’  提交commit 引号中是提交信息
- git reset --soft HEAD^ 撤回上次commit到本地
- git status 显示代码库状态
- git log 打印提交信息
- git diff 对比提交代码
- git reset —hard …..	恢复之前版本省略号是code码 
- git reset —hard 恢复上一版本
- git commit -m ‘…..’  提交commit 引号中是提交信息
- git rm …. —cached	git 删除远端文件并且储藏
- git revert -m 1 d029fb25aa62bfdf20935b7b1c8bddd20d120032     恢复版本
- make tag-release  tag命令 
- git push origin —tags 提交的时候git上会有一个版本升级的界面
- git tag -d v2.0.4   删除某个tag
- git push origin :refs/tags/v2.0.4    删除远端签名


#### 2. 常用npm命令

- npm unpublish ….	移除某个包或者版本
- npm version patch 升级版本
- npm publish --access public --dry-run  npm 发包干运行
- npm publish --access public  npm 发包


#### 3. 常用yarn命令

- yarn remove ...  移除包
- yarn add --dev …  安装到生产环境 devDependencies
- peerDependencies  表示如果使用我这个包， 下载我这个包的项目也必须安装这个里面的包

#### 4. linux 命令

- sudo nginx -t 测试配置文件是否有语法错误
- sudo nginx -s reload 重新加载配置文件 然后以优雅的方式重启nginx
- sudo nginx -s stop 强制重启nginx 服务
- sudo nginx -s quit 优雅重启nginx 服务（处理完所有请求）

ps aux |grep nginx

ps：要对进程进行监测和控制,首先必须要了解当前进程的情况,也就是需要查看当前进程,而ps命令就是最基本同时也是非常强大的进程查看命令.使用该命令可以确定有哪些进程正在运行和运行的状态、进程是否结束、进程有没有僵尸、哪些进程占用了过多的资源等等.总之大部分信息都是可以通过执行该命令得到的.

ps 后面的值

-e 显示所有进程。
-f 全格式。
-h 不显示标题。
-l 长格式。
-w 宽输出。
a 显示终端上的所有进程，包括其他用户的进程。
r 只显示正在运行的进程。
u 　以用户为主的格式来显示程序状况。
x 显示所有程序，不以终端机来区分。

grep 命令是一种强大的文本搜索工具，它能[使用正则表达式]搜索文本，并把匹 配的行打印出来。grep全称是Global Regular Expression Print，表示全局正则表达式版本，它的使用权限是所有用户

