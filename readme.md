##  route  mvc(经典的网站开发模式)中的一环
    resetful 网站的本质就是提供资源访问
    url => 资源 一一对应关系
    ?queryString1=a&queryString2=b
    backend 来做 自有路由规则 route
    mvc 解析url，映射一个route跟后端脚本对应的controller
    fontend 接管一切
    前端跟服务器的相关性问题
    url => 资源  缺点，http
    href 刷新页面 用户体验不好
    https://m.taobao.com/#index 前端url规则
    https://m.taobao.com/#home
    html5 historyAPI
    前端url 就好像切换一张小卡片 整个页面都没有动。=>单页应用(SPA)SinglePageApplication
    动态更新界面？前端url规则 启动,交给ajax
    跟vue的关系=>  url=>page=>组件


