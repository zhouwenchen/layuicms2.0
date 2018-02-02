```
本模版已进行作品版权证明，不管以何种形式获取的源码，请勿进行出售或者上传到任何素材网站【同时也请各站长自觉遵守】，否则将追究相应的责任
```
### 为我点赞
http://fly.layui.com/case/u/3198216
```
此模版继续沿用原有规则，即学习交流完全免费，商业用途联系作者授权。
技术交流及商业授权联系，企鹅群：576881857
```
### 模版效果预览
首页
![首页](https://gitee.com/uploads/images/2018/0131/110933_38bfb6cc_1404064.jpeg "QQ截图20180131110811.jpg")
个人资料
![个人资料](https://gitee.com/uploads/images/2018/0131/110954_76645863_1404064.jpeg "QQ截图20180131110823.jpg")
文章发布
![文章发布](https://gitee.com/uploads/images/2018/0131/111048_388796de_1404064.jpeg "QQ截图20180131110844.jpg")
使用文档
![使用文档](https://gitee.com/uploads/images/2018/0131/111113_a073dc5d_1404064.jpeg "QQ截图20180131110908.jpg")
### 更新日志
- 顶部高度修改为了50px，如果有朋友感觉还是原来的高度更好，请将index.css文件中最底部的4行样式去掉即可，有注释
- 郑重提示：由于后期会对此框架进行多次开发，基本上修改的是大框架，所以强烈不建议对index.js/bodyTab.js进行修改，以便后期的更新能够直接覆盖升级。【以后主要侧重组件开发和功能优化，由于能力有限，请大家多多担待】
- 框架采用最新的layui2.x进行对1.0版本的重写，完全不同于1.0版本的模版，不能覆盖升级
- 由于本人对设计和色差之类的不太感冒，所以一些布局和颜色搭配不是太完美，在此跟大家说声抱歉，大家可以根据自己的喜好进行一些调整。
- 新增“系统日志”、“会员等级”、“图标管理”、“使用文档”等页面，新增“功能设置”、“清除缓存”、“编辑文章”等功能
- 由于后期将会整合layIM，所以将原有的“消息”页面删除了，虽然会整合layIM，但是不会提供layIM的下载，如果有需求的朋友可以去进行layIM的授权 
- 删除天气组件【感觉没什么作用，如果需要的可以自行去“心知天气”或另外的第三方组件中设置添加】
- 由于项目是响应式，但是table不支持响应式，所以拖动浏览器改变分辨率的情况table可能展示不太友好，之前用window.resize()方法实现了托动改变大小，但是发现每拖动1px就会请求一次接口，所以舍弃了这个方法
- 对搜索模块的位置进行了调整【后面小版本中会提供搜索跳转/打开新窗口功能】
- 由于数据表格的分页、搜索、添加、删除等一系列数据操作需要接口的配合，同时大家都了解这是一套纯前端模版，没有后台，所以这些操作都没有了。有人提议用js动态截取json去实现动态效果，这样当然可以，但是身为一个有严重洁癖的码农，如何能忍受这样的情况？所以这些就需要大家在实际使用中根据接口传参实现了。
- 重构页面图标【由于layui2.0新增了许多图标，所以对原有的图标进行了重构，避免图标冗余。实际使用中建议自己去阿里图标库挑选符合网站风格的进行替换】
- 优化刷新当前页面，关闭其他，关闭全部等按钮造成的bug
- 增加顶部一级菜单用以实现三级菜单，并实现响应式。可以通过更改浏览器的分辨率并且点击顶部菜单来查看效果，这个功能做了一天多啊【后面的小版本会对此功能进行优化，即增加反向定位功能】
- 对90%以上的页面进行了样式优化和微调，使其更加完美【对于有强迫症的我来说，有一点瑕疵都是不能容忍的】
- 由于模版中的动态操作基本都是通过缓存完成的，所以为了避免缓存过多造成卡顿现象，增加“清除缓存”按钮
- 添加自定义是否开启Tab缓存【即刷新页面后是否重新打开刷新前的窗口】、是否切换窗口刷新页面、单一登录等功能。【在功能设定弹窗中设置，在移动端已隐藏此功能】功能其实早就有朋友提出来过，一直没有想到好的方式添加，直到larry的模版出来，感觉方式不错，借鉴了一下他的这种模式，在此对larry表示感谢
- 优化更换皮肤在升级为2.x版本后无效的问题【后期会针对此功能进行深入优化，在移动端已隐藏此功能】
- 优化“点赞、码云、github”链接。【之前虽然也有模版下载链接按钮，不知道是不明显还是什么，总有人私聊我要源码，这次我把按钮改大点，如果你们再看不到，那就不是不明显了。。。】
- 优化“个人资料”页面，修改布局和响应式展示样式，重写地区三级联动效果【已封装成模块】，代码更简洁。【由于静态数据不能通过post方式提交，否则会报405、500错误，所以为了演示，将请求方式修改成了get，在实际使用中请将userInfo.js中的第13行删除，有注释】
- 重做404页面、登录页面，增加动画效果。闪瞎你的钛合金眼
- 新增“图标管理”页面，用于展示引入的第三方图标文件。可点击复制class到想要的地方
- 新增“使用文档”页面，详细描述了模版中封装模块的各个功能，让使用者更加了解封装的模块的功能
- 通过减少列来使table在移动端保持正常显示。需要列足够少，控制在2-3列最好。只需要给在移动端不显示的td添加pc属性即可，如<td pc>此单元格在移动端不显示</td>。如果还是理解不了请查看“系统基本参数”页面或者“使用文档”页面
- 全面优化缓存机制，例如只要在“个人资料”页面修改过头像，那其他有头像的地方都会展示修改后的头像；修改“系统基本参数”后刷新页面底部版权修改等【当然这个功能在实际开发中就是个鸡肋，没有什么实际用处，在此处我只是想做个功能展示，毕竟这套模版是不包含后台的】
- “文章列表”页面新增文章编辑功能和预览，另外优化了搜索功能【编辑和优化功能都需要接口配合，预览功能需要前后台配合】
- 重做“添加文章”页面，使其更加适合实际开发中使用【当然这是我以为的，在实际使用中肯定还差很多功能，后面会慢慢完善】编辑器由于本身的问题，点击列表中的编辑按钮有时会赋不上值，请暂时无视，等到layedit重写后重做
- “图片管理”页面新增“上传新图片”和“图片展示【即layer.photo】”功能。【由于弹层的展示获取的是接口中的数据，所以弹层不会展示新上传的图片，当然实际开发中不会有这个问题】
### 开源协议
MIT License
### 在线预览
http://layuicms.gitee.io/layuicms2.0/index.html
