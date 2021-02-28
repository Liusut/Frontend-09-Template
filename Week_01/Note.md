学习总结：
1、TicitacToc中的 clone函数 用JSON.parse(JSON.stringify(Array))克隆一个新的对象
2、函数或括号内逻辑都具有作用域
3、js outer中的用法
4、回调地狱的认识
5、无限循环的小技巧 while(true)
5、Promise的用法和语法
	function fnc(){
		return new Promise((resolve,reject) => {
			...
		})
	}
6、aysnc await的用法
	aysnc function fnc(){
		while(true){
			await ...
		}
	}