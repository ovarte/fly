# [require.js](https://github.com/browserify/browserify/edit/master/security.md)

定义一个模块 /js/demo.js
```js
    define(function () {
        //Do setup work here

        return {
            color: "black",
            size: "unisize"
        }
    });
```

引用定义的模块 /main.js

```js
   requirejs(['js/demo'],function($,canvas,) {
       //Do setup work here
    });
```
