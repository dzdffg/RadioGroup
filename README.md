# KeyRadioGroup
==============
* 支持多行多列的复杂布局的RadioGroup<br>
* Multiple rows and columns RadioGroup<br>
    * If U don't understand the Chinese Notes. <br>
    Please use the V1 version.You can write any layout under \<KeyRadioGroupV1>
    <br>
    
===========
* 1.2 更新，做了向下兼容，现在全版本可以使用<br>

==============
## 使用方法
>使用方法很简单，把widget包，或者你用的版本（V1或V2）丢到你的工程里，XML里用对应的标签就可以了，里面写有demo，可以参考<br>
>V1支持任何复杂的布局<br>
>>通过递归布局内部的RadioButton来实现的<br>

========
>V2只支持标签下再添加一层布局<br>
>>为了简单方便效率高，和考虑到实际用途，没写递归的方法，只能用一层布局，哪怕你一行只有一个RadioButton你也要在外面包一个Layout，只要是ViewGroup的子类都可以<br>

==========
>我是参考12.6K的RadioGroup源码写的。从API20开始是这个版本的源码。之前的是12.9K的，只相差一个获取名字的方法<br>

==========
>我试过直接继承RadioGroup来重写，但是没成功，而且这样继承，很多父类的方法不能直接调用，我也不知道是什么原因，如果有人知道，可以发邮件给我，感谢指点<br>

=================
=================
有什么BUG和建议，大家可以发邮件跟我讨论<br>
我的邮箱：mrkey.k@gmail.com<br>

![KeyRadioGroup](https://github.com/Key-CN/pic-apk/blob/master/KeyRadioGroup.png)
