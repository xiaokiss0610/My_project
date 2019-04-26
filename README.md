使用方法

1,在页面中引入cityselect.js和样式文件cityselect.css。

        <link rel="stylesheet" type="text/css" href="css/cityselect.css">
        <script src="path/to/cityselect.js" type="text/javascript"></script>

2,HTML结构

使用一个<input>输入框，为它添加ID。

        <input type="text" class="cityinput" id="citySelect" placeholder="请输入目的地">
3,初始化插件

在页面加载完毕之后，通过下面的方法来初始化该插件。

        var test=new Vcity.CitySelector({input:'citySelect'});  

