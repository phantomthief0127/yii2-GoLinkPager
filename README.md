# yii2-GoLinkPager
yii2 带跳转到具体某页和共多少页的分页扩展

**教程文档**

你可以[点击这里](http://www.manks.top/yii2-linkpager-widget.html)查看具体详细的教程文档

**使用**

使用时设置go为true即可，默认为false不显示

```
// 添加具体的所在目录 如
use common\components\GoLinkPager;

// 使用
GoLinkPager::widget([ 
    'pagination' => $pages, 
    'go' => true, 
]);
```
