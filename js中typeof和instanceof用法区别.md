#typeof和instanceof的区别
typeof和instanceof都可以用来判断变量，它们的用法有很大区别：
typeof会返回一个变量的基本类型，只有以下几种：number,boolean,string,object,undefined,function；例：
alert(typeof(1));//number
alert(typeof("abc"));//string
alert(typeof(true));//boolean
alert(typeof(m));//undefined
