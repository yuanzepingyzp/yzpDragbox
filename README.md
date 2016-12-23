# yzpDragbox
基于angularjs及iframe的可拖动框组件
##EXAMPLE CODE
###html code
```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<link rel="stylesheet" type="text/css" href="style.css">
	</head>
	<body ng-app="app">
		<yzp-dragbox title="yzpDragtitle" src="file:///C:/Users/yWX429287/Desktop/yzpInput/index.html" x=0 y=0></yzp-dragbox>
		<script type="text/javascript" src="angular.js"></script>
		<script type="text/javascript" src="yzpDragbox.js"></script>
	</body>
</html>
```
##API
```html
<yzp-dragbox title="yzpDragtitle" /*define the title of the drag box*/
              src="file:///C:/Users/yWX429287/Desktop/yzpInput/index.html" /*define the src of the iframe*/
              x=0 /*define the oragin position of the dragbox left*/
              y=0 /*define the origin position of the dragbox top*/
              ></yzp-dragbox>
```
