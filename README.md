##这个widget是干什么的

一个可以在你的页面显示你的github个人信息的jquery widget组件。

##这里是[demo](http://htmlpreview.github.io/?https://github.com/bh-lay/github-widget-user/blob/master/demo.html)

![demo](resources/demo.jpg)
##如何使用

###1、傻瓜式
只需要在引入`jquery-github-user-widget.js`文件，在页面中创建一个class为`github-widget-user`的dom，在data属性上增加用户参数即可。

```html
<div class="github-widget-user" data-user="bh-lay"></div>
```

###2、自定义式
用于js交互比较频繁的场景，同样是引入`jquery-github-user-widget.js`文件，在需要使用时书写如下代码。

若对应dom上有`data-user`参数，JS函数中可以省略用户名参数，两者有冲突时，以JS传入为优先。
```javascript
    $('.some_class').github_user_widget('bh-lay');
```
