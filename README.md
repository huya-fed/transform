# transform 使用文档



## 例子

[https://github.com/AlloyTeam/AlloyTouch/tree/master/transformjs](https://github.com/AlloyTeam/AlloyTouch/tree/master/transformjs)


## API

	Transform(domElement, [notPerspective]);


## Usage


	Transform(domElement);//or Transform(domElement, true);
	
	//set "translateX", "translateY", "translateZ", "scaleX", "scaleY", "scaleZ", "rotateX", "rotateY", "rotateZ", "skewX", "skewY", "originX", "originY", "originZ"
	domElement.translateX = 100;
	domElement.scaleX = 0.5;
	domElement.originX = 0.5;
	
	//get "translateX", "translateY", "translateZ", "scaleX", "scaleY", "scaleZ", "rotateX", "rotateY", "rotateZ", "skewX", "skewY", "originX", "originY", "originZ"
	//console.log(domElement.translateX )


