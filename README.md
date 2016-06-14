# 前端面试题
	1 变量作用域
		(1) this指向
		(2) setTimeout中this指向
			for(var i=0;i<3;i++){
				setTimeout(function(){console.log(i)},1000)
			}
		(3) 如何改变this指向
	2 继承
		call apply
	3 安全
		(1) xss
		(2) crsf
	4 性能优化
		(1) 静态资源优化
		(2) js
	5 跨域
		jsonp iframe postmessage
	6 构造函数
		var a={x:2}
		function aa(a){
		  a.x=1
		  a={}
		  console.log(a)
		}
		aa(a)
		//Object {}
		console.log(a)
		//Object {x: 1}
