玩家一  玩家二。。。。
类 object
json object 难以完成这个任务
function 
玩家类 es5之前 没有class 关键字
 大写首字母的函数 构造函数

 将类实例化    类抽象的概念，对象可以new出来

- 什么是this?
- 函数有多种运行方式
    Player() 普通方式，
    new Player() 作为构造函数constructor被运行,会有返回新对象 实例
    构建函数，当然是类，
    function Person()   { }

- 函数是一等对象，它是一个可以被执行的对象，
    this 常在 借助this来构造新的对象
    new player1 = new Person()
    this => player1     Person{}

- new的过程
  this 空对象Person {} 
  Person() 构造函数，
  this.name = name;
