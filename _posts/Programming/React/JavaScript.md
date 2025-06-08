# JavaScript

- `constructor()` 构造器方法,是个关键字

-   ~~javascript好像没有实例方法,所有方法放在类中.~~ 直接声明是static静态方法,如果赋值了就在实例  
    ```jsx
    //类中
    someWay(){};
    
    //实例中
    someWay=function(){};
    
    someWay=()=>{};
    ```
- 属性写了`static`是静态,方法不写static就是静态
- 在Javascript中的方法可以不需要实例调用.  
onclick调用的方法为直接调用.this为Window(严格模式为undefined)

- `bind` 生成新的函数,并且改变触发者. 

-   return 不能换行
    ```js
    return <></>
    //return不能换行,下面是错的
    return 
    <></>
    ```
-   `console.log(...arg)` arg为数组.该代码会复制一个新的数组,输出的时候会foreach
-   `export`可以在其他文件中访问
-   `default`表示此为主要函数

## 样式

.css

`import "./some.css"` 当前目录下的某个css

>[!WARNING]
>空字符默认顶端与父表格顶端对齐，加入字体后则会对准文字基线(baseline),所以以下直接设置`top`,全部顶端对齐,就不会位置变化  
>`vertical-align:middle` 文字的下行线

----
javacript 感觉不太规范，有点乱  
可能ES6之后的好一点