1、OC、swift的protocol区别
2、Swift如何实现动态性
3、Swift派发机制： 直接派发、函数表派发、消息机制派发
为什么Swift类扩展里面的方法无法动态加入该类的函数表中，只能使用静态派发的方式？
4、String、array、dictionary 为什么设计成值类型
5、optional的wrap、unwrap
6、static和class的区别
    static可以用在值类型、class不行
    static修饰的不可以被继承，class修饰的可以被继承
7、Copy-on-write: 值类型在赋值的时候两个对象是指向同一个内存，只有在一个对象进行修改的时候才会在内存中产生一个新对象进行的是深拷贝
8、关键字 final dynamic @objc
