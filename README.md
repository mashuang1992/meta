# meta
meta声明

```
<head>
		<meta charset="utf-8">
		<title></title>
		<meta name="description" content="" />
		<meta name="keywords" content="" />
    /*视口属性 **/
		<meta name="viewport" content="width=device-width,initial-scale=1.0,user-scalable=no">
    
    /*页面缓存 **/
    <meta http-equiv="pragma" content="no-cache"> 
    <meta http-equiv="cache-control" content="no-cache"> 
    <meta http-equiv="expires" content="0">
    
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE7"> //兼容ie7用来指定IE浏览器解析编译页面的model

     <meta content="text/html; charset=UTF-8" http-equiv="Content-Type">  //页面要做解析使用字符集.html文件，标准加载，避免乱码

     <meta http-equiv="X-UA-Compatible" content="IE=edge">  //主要是设置浏览器优先使用什么模式来渲染页面的，兼容ie微软edge内核浏览器
     
     使用最高级的ie内核，如果支持谷歌内核，使用谷歌内核
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />        

     <meta content="e-Learning 使用户能够自由地分配学习时间，制定专属于自己的培训计划。" name="Description"> //在线学习或网络化学习.

     <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">  //自适应移动端，初始缩放比例，也即是当页面第一次 load 的时候缩放比例。width：控制 viewport 的大小，可以指定的一个值，如果 600，或者特殊的值，如 device-width 为设备的宽度（单位为缩放为 100% 时的 CSS 的像素）。

     <meta content="企业内训解决方案，企业延展培训解决方案，移动学习解决方案，分布式部署解决方案" name="Keywords"> //关键字

     <meta content="App" name="msApplication-ID"> //app端的应用  rel是rel="stylesheet" 是关联表


     <meta name=”renderer” content=”ie-comp”> //兼容360浏览器极速模式和标准模式

     <meta name=”renderer” content=”ie-stand”>

     <meta http-equiv="X-UA-Compatible" content="IE=8"> //兼容ie8

     <meta http-equiv="X-UA-Compatible" content="IE=7,IE=9"> //兼容ie9

     <meta http-equiv="X-UA-Compatible" content="IE=Edge,chrome=1"> //兼容360内核浏览器
     <meta name="renderer" content="webkit|ie-stand|ie-comp" />             

     <link rel="icon" href="<%= BASE_URL %>favicon.ico">

     <meta http-equiv="X-UA-Compatible" content="IE=11">                     //兼容ie11

     <meta name="renderer" content="webkit">                                 //兼容谷歌浏览器内核


```


