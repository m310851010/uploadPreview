uploadPreview jQuery插件
==============================

这是一个jQuery插件。用于把图片上传到服务器之前能够在本地预览图片。兼容IE6+、FF、Chrome浏览器。

使用说明:
1.首先页面需要引入jQuery库,然后引入uploadPreview.js,例如如下代码:

<script type="text/javascript" src="jquery-1.7.1.min.js"></script>
<script type="text/javascript" src="uploadPreview.js"></script>

2.然后在HTML页面中需要一个文件域和一个预览图片的容器,通常是一个<div/>,例如如下代码:
<div id="container"></div>
<input type="file" name="file" id="file" />

3.在js中编写代码调用uploadPreview函数即可,例如如下代码:
$('#file').uploadPreview({container:'#container'});