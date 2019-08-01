# interview
# 每日三问——0429
> [github项目](https://github.com/haizlin/fe-interview?utm_source=ZHShareTargetIDMore&utm_medium=social&utm_oi=750848792785354752) 问题解答
# HTML
### html5中的form怎么关闭自动完成？
自动完成允许浏览器预测字符段的输入，当用户开始键入时，浏览器会基于显示历史输入列表，自动完成默认值为on，当设置autocomplete="off"时关闭
# CSS
### ::before和:after中单冒号和双冒号的区别是什么，这两个伪元素有什么作用？
在CSS3中，为了和伪类区分开来，伪元素使用双冒号显示
> ::before，在元素前面添加内容
> ::after，在元素后面添加内容
# JS
### 说说你对javascript作用域的理解
> 全局作用域，在全局范围内都可以调用
> 局部作用域，只可以在函数内调用，函数外无法调用
> 作用域链，在函数预编译时会生成执行期上下文，这时会把函数内的局部变量储存在AO中，当函数调用变量时，首先在自己的AO中查找，当找不到变量时，将逐层往上查找，一直找到全局GO中。
