# AWStats-Themes-HomePage

一个静态个人主页，基于 [AWStats](https://github.com/lete114/AWStats) 静态生成器生成的静态个人主页

# 使用

> 前提是你得先克隆 [AWStats](https://github.com/lete114/AWStats) 项目，cd进入AWStats，执行下方命令克隆本项目到AWStats的themes目录下

```bash
git clone https://github.com/lete114/HomePage themes/HomePage
```

修改AWStats的`config.yml`配置文件
```yml
themes: HomePage
```

# 配置文件

```yml
#--------------------------------------------------------
# AWStats-Themes-HomePage
# 项目地址：https://github.com/lete114/HomePage
# 演示地址：https://www.lete114.top/
# 一个静态个人主页
#--------------------------------------------------------


# language 语言
language: zh-CN
author: Lete乐特 # author 名称 
avatar: /img/avatar.png # avatar 头像
favicon: /img/favicon.ico # favicon 图标
desc: 我相信我可以，但我一直在路上，所以我有无限的可能！！<br>人生只有一次，大胆的生活，怎么舒服怎么来！！ # 个人描述
description: 我相信我可以，但我一直在路上，所以我有无限的可能！！ # description 网站描述
keywords: Lete乐特,Java,JavaWeb,Java常用框架,Spring,SpringBoot,SpringMVC,MyBatis,数据库,MySQL,C#,.NET,开发工具,Git,GitHub,Gitee,(My)Eclipse,IDEA, Hexo,Linux,Maven,前端基础知识,HTML,CSS,JavaScript,jQuery,Ajax,Bootstrap,工具&#x2F;资源,教程,分享,推荐,娱乐,摄影,C#,CMD,Developer,Programmer,Coder #关键字

since: 2019 # 开启主页年份

# 图标大小
font_size: 1.6em
# Icon 图标
links:
  iconfont icon-youxiang: mailto:lete@lete114.top
  iconfont icon-github3: https://github.com/lete114
  iconfont icon-icon_doc_fill: https://blog.lete114.top
  iconfont icon-lianjie: https://blog.lete114.top/link/
  iconfont icon-csdn: https://me.csdn.net/Lott0419
  iconfont icon-zhihu: https://www.zhihu.com/people/lete114


# 自定义页脚字体颜色
footer_color: '#000 '
footer_a_color: '#000'

# 鼠标移动到超链接上显示的颜色
a_hover: '#e58a8a'
# 自定义名称颜色
author_color: '#80bdab'
#自定义描述字体颜色
desc_color: '#000'

# 自定义背景
# bg_img: url(https://cdn.jsdelivr.net/gh/lete114/CDN2/img/wei_er_li_te/3.jpg)
# bg_img: '#fff'
# bg_img: 'white'
bg_img: url(https://cdn.jsdelivr.net/gh/lete114/CDN2/img/wei_er_li_te/3.jpg)




# 自定义引入外部css、js
import:
  head: # 引入到</head>之前
    - 
  top: # 引入到<body>之后
    - <link href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free/css/all.min.css">
    - <style>.icon-icon_doc_fill{color:#e58a8a;}</style>
  bottom: # 引入到</body>之前
    - 
  # 例如： 
  # - <link rel="stylesheet" href="/css/index.css">
  # - '<style>body{color: red}</style>' ## 注意由于css的‘{}’是关键符号所以需要(单/双)引号''
  # - <script>alert(1)</script>


## 404页面
error_404:
  background: '#00c4b6'

# ICP备案
ICP:
  enable: false
  icon: img/icp.png
  url: http://www.beian.miit.gov.cn/
  text: 
  
# 分析(统计)
analytics:
  baidu:  # 百度分析
  google: # 谷歌分析


CDN:
  index: /css/index.css
  iconfont: /css/iconfont.min.css

  pixi: https://cdnjs.cloudflare.com/ajax/libs/pixi.js/2.2.5/pixi.js
```
