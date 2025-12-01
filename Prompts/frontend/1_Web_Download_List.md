# 需要下载的页面和保存的本地路径

目标：下载 12306 相关页面的完整内容
保存路径：./Frontend/data/

需要下载的页面：
1. 首页 - https://www.12306.cn/index/
   保存到：首页/index.html 及相关资源

2. 购票页面 - https://kyfw.12306.cn/otn/leftTicket/init?linktypeid=dc
   保存到：购票/index.html 及相关资源

3. 登录页面 - https://kyfw.12306.cn/otn/resources/login.html
   保存到：登录/index.html 及相关资源

4. 注册页面 - https://kyfw.12306.cn/otn/regist/init
   保存到：注册/index.html 及相关资源

要求：
1. 你需要先实现一个python脚本（使用sync_playwright库），路径为./tmp/，它的目的是用浏览器打开特定的网页，并且在网页全部加载成功后，在网页中按ctrl+s（或者点击鼠标右键，再点击另存为按钮），之后，你需要在弹出的保存对话框中，将文件保存到指定的路径（比如./Frontend/data/首页/index.html），注意保存网页的类型应该选择全部（*.html;*.html）。
2. 执行该脚本，下载所有页面的内容。
3. 所有任务完成后，删除该脚本

请逐步执行并报告进度。