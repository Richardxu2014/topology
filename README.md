# topology
## 说明

基于raphael.js实现的，可拖拽的拓扑图控件，支持圆形，横版树形，垂直树形三种暂时方式，图形，字体，画布大小，连接线等等所有东西都可以配置

## 参数配置
```javascript
//初始化参数，一下为默认值，可选择性自定义，
    /*var initparam = {
        node: '#svg-container-edit',//node：#加画布外层divID
        width: 600,  //画布宽度
        height: 600,  //画布高度
        nodecirclemax: 30,  //节点半径最大值
        nodecirclemin: 20,  //节点半径最小值
        nodestrokecolor: '#3F3E3E', //节点轮廓颜色 默认
        nodestrokewidth: 0.5,     //节点轮廓粗细
        nodeTextColor: '#fff',  //节点中字体的颜色,
        nodeTextSize: '14px',  //节点中字体的大小
        nodeTextWeight: '600',  //节点中字体的粗细
        paperFilletStroke: "#666",//画布圆角轮廓颜色
        paperFilletRadius: 10,//画布圆角半径
        mode: 'edit',   //edit为可移动 view为不可移动
        totallevel: 5,  //总层数
        showstyle: 'tree_H',  //展示风格 doughnut:圆环图；tree_H:横向树形图；tree_V：垂直树形图
        lintwidth: '2px',    // 链接线宽
        lintcolor: '#C6D9EC',    // 链接线宽
        middlePiont: 9,       // 链接线中间点半径
        middlePiontFill: '#BED8EC',       // 链接线中间点填充颜色
        middlePiontStroke: '#C6D9EC',       // 链接线中间点轮廓颜色
        middlePiontText: '?',     // 中间点内文本
        middlePiontTextColor: '#fff',       // 中间点内文本颜色
    }
    */

```

---------------------------------------
此为2014年做的一个控件发布在 [***JCSDN***](http://download.csdn.net/download/wer12123/6909649) , 后来CSDN密码忘记了，最近整理电脑中的文件，偶然看见这个项目，随即整理了一下并提交到了gitlab