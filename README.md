# ExpressWebPostSample
A node.js app, web form post data to server example.


这个案例是使用button来进行提交，将整个表单提交到后台

res的body中会收到一个对象

测试结果node.js端(注意这里的key是前端input的name，例如：name="first_name" )

{
first_name:'Dezhi',
last_name:'Wang',
email_addr:'wdz0077@163.com'
}

