# 开启你的个人博客之旅

> 首先欢迎您的阅读，然后其实我觉得这个博客系统太简单了，期待您的pull request

### 前言

- 先看看例子：[林志鑫的个人博客](https://amenrun.github.io/blog/)
- 如果你喜欢，就fork me吧

### 开始使用

1. 浏览器的标签头上面的小图标
   - 选择一张你喜欢的图片，到时候是会展示在浏览器标签头那里，尺寸大小制作成16*16(px)，命名为favicon.ico，放在根目录下
   - 在根目录的favicon.ico，原先是我制作的icon，记得把你自己制作的替换掉它

2. 给你的文章分类别
   - 打开 ./p/projects/ ，创建一个文件夹，给它起个名字表示一种类别的文章，然后进入该文件夹
   - 可以参考我创建的 ./p/projects/markdown/ 文件夹里面的结构，article文件夹存放和markdown有关的文章，image文件夹存放你想在这些文章展示的图片，而index.md文件你可以用来对这个类别的文章起一个目录导航的作用

3. 博客的左边是导航栏
   - 打开 ./p/sidebar.md ，给你的文章设置索引，注意使用相对路径
   - 可以参考我设置的索引结构

4. 博客的右边是文章浏览区
   - 打开 ./p/aboutme.md ，给你的博客编辑首页内容，可以参考我编辑的首页
   - 如果你按照以上步骤来，你总能在右边浏览文章
   - 有问题搞不定，请联系我

### 使用github pages

1. 进入你的github账号
2. 点击头像进入settings
3. 向下拉找到GitHub Pages栏，其中粗体字Source下面有两个按钮
4. 点击左边按钮，选择master branch
5. 然后点击右边按钮Save
6. 搞定，再回来 settings--GitHub Pages栏，你会看到“Your site is ready to be published at https://xxxxxxx”这就是你博客的链接啦，点击看看

### 感谢您的支持，祝您生活愉快