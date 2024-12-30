# [Hugo Academic CV Theme](https://github.com/HugoBlox/theme-academic-cv)

[![Screenshot](./preview.png)](https://hugoblox.com/templates/)

# 个人主页

[**个人主页链接**](https://zhinchenFD.github.io)


主页内容在`content\_index.md`下

论文信息放在`content\publication`下

## 本地调试

左上角任务栏选择终端->新建终端,开启终端后右下角打开git bash终端，输入`hugo server`开启本地服务。

之后浏览器访问http://localhost:1313/ 即可观察到预览效果。

## 提交至github网页端

内容修改好后，同样打开git bash终端，输入`git add .`，这个指令会把当前目录下的文件改动添加到git项目管理流中。

接着，输入`git commit -m "(此处更改为需要记录的修改信息，例如：update：更新了news界面,用引号包裹住)"`，这个指令会确认我们做出的修改。

最后，输入`git push`，这个指令会把修改的内容提交给github，此时就能在网页上看到个人主页的修改了。
