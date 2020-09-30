forkme
======
随着我国科技水平不断发展，玩Github的童鞋越来越多了，按照惯例，开源项目会有一个示例网站，而网站的右上角，通常会有一个forkme on github，这说明你可以去Github查看、下载项目源码。  
这明显是个通用样式，但小菜找了找，没发现有这种插件。。。  
于是小菜动手写了一款小插件，命名为forkme，专门用来在网站右上角添加一个forkme on github的小菜单。  
废话不多说，直接上例子：  
  
    <!DOCTYPE html>
    <html>
      <head>
        <title>How To Use Forkme  ok</title>
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <!--引用forkme样式-->
        <link rel="stylesheet" href="./css/forkme.css">
      </head>
      <body>
        <!--引用jquery-->
        <script src="./js/jquery-1.8.2.min.js"></script>
        <!--引用forkme脚本-->
        <script src="./js/forkme-1.0.js"></script>
        <script>
          //渲染forkme
          //第一个参数是显示的文本
          //第二个参数是链接地址
          $(document).ready(function(){
            $("body").forkme("View Forkme","https://github.com/");
          });
        </script>
      </body>
    </html>
