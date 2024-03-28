# Vue
前端练习代码

## 此repository仅用于学习vue的代码储存



**2024年3月28日**

又重新看了一遍jwt



jwt可以使用对称加密也可以使用非对称加密

---

非对称加密即 使用私钥进行加密 公钥进行解密



## java-jwt的使用

调用JWT的create方法再链式调用withClaim（k，v）

signWith(alg) 然后就返回一个string

使用ex开头的限定时间 传的参数是Date类型的

可以使用 

> Date date = new Date();
>
> date.set(date.getDate() + 1000 * 60 * 60 * 24 * 7 )
>
> 从现在起的七天内有效
