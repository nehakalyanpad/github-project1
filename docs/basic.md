# Basic 基础练习

## Demo-1

* 有如下值集合 [11,22,33,44,55,66,77,88,99,90]，将所有大于 66 的值保存至字典的第一个key中，将小于 66 的值保存至第二个key的值中。
* 即： {'k1': 大于66的所有值, 'k2': 小于66的所有值}

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo1.py)

## Demo-2

* 查找列表中元素，移除每个元素的空格，并查找以 a或A开头 并且以 c 结尾的所有元素。

```python
li = ["alec", " aric", "Alex", "Tony", "rain"]
tu = ("alec", "aric", "Alex", "Tony", "rain")
dic = {'k1': "alex", 'k2': ' aric', "k3": "Alex", "k4": "Tony"}
```

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo2.py)


## Demo-3

* 输出商品列表，用户输入序号，显示用户选中的商品

```python
li = ["手机", "电脑", '鼠标垫', '游艇']
```

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo3.py)


## Demo-4

* 要求用户输入总资产，例如：2000
* 显示商品列表，让用户根据序号选择商品，加入购物车
* 购买，如果商品总额大于总资产，提示账户余额不足，否则，购买成功。
* 附加：可充值、某商品移除购物车

```python
goods = [
    {"name": "电脑", "price": 1999},
    {"name": "鼠标", "price": 10},
    {"name": "游艇", "price": 20},
    {"name": "美女", "price": 998},
]
```

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo4.py)


## Demo-5

* 用户交互，显示省市县三级联动的选择

```python
dic = {
    "河北": {
        "石家庄": ["鹿泉", "藁城", "元氏"],
        "邯郸": ["永年", "涉县", "磁县"],
    },
    "河南": {
        "石家庄2": ["鹿泉2", "藁城2", "元氏2"],
        "邯郸2": ["永年2", "涉县2", "磁县2"],
    },
    "山西": {
        "石家庄3": ["鹿泉3", "藁城3", "元氏3"],
        "邯郸3": ["永年3", "涉县3", "磁县3"],
    }
}
```

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo5.py)

 ## Demo-6

* 在old中，删除old中存在，new中不存在的
* 在old中，新建new中存在，old中不存在的
* 在old中，更新两个中都存在的

```python
old_dict = {
    "#1": 11,
    "#2": 22,
    "#3": 33
}

new_dict = {
    "#1": 11,
    "#3": 44,
    "#4": 100
}
```

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo6.py)

 ## Demo-7

* 简述普通参数、指定参数、默认参数、动态参数的区别?


 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo7.py)

 ## Demo-8

* 写函数，计算传入字符串中【数字】、【字母】、【空格] 以及 【其他】的个数


 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo8.py)

 ## Demo-9

* 写函数，判断用户传入的对象（字符串、列表、元组）长度是否大于5


 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo9.py)

 ## Demo-10

* 写函数，检查用户传入的对象（字符串、列表、元组）的每一个元素是否含有空内容。


 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo10.py)

 ## Demo-11

* 写函数，检查传入列表的长度，如果大于2，那么仅保留前两个长度的内容，并将新内容返回给调用者。

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo11.py)

 ## Demo-12

* 写函数，检查获取传入列表或元组对象的所有奇数位索引对应的元素，并将其作为新列表返回给调用者。

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo12.py)

 ## Demo-13

* 写函数，检查传入字典的每一个value的长度,如果大于2，那么仅保留前两个长度的内容，并将新内容返回给调用者。

```python
dic = {"k1": "v1v1", "k2": [11,22,33,44]}
PS:字典中的value只能是字符串或列表
```

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo13.py)


 ## Demo-14

 * 随机产生四位字母或数字组成的验证码

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo14.py)

 ## Demo-15

 * 命令行实现用户登录、注册操作，并以文本文件保存用户名密码数据

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo15/user.py)

 ## Demo-16

 * 实现多层装饰器及任意传参

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo16.py)

 ## Demo-17

 * 利用生成器实现并行效果

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo17.py)

 ## Demo-18

 * 正则判断输入的邮箱是否合法

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo18.py)

 ## Demo-19

 * 实现命令行进度条，带百分比

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo19.py)

 ## Demo-20

 * 利用第三方接口和第三方模块实现输入QQ号判断是否在线

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo20.py)

 ## Demo-21

 * 实现配置文件的增删改查

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo21.py)

 ## Demo-22

 * python日志模块

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo22.py)

 ## Demo-23

 * 基于反射实现简单路由模块函数功能

 参考Demo：[链接](https://github.com/mgss/python-demo/blob/master/example/basic/demo23.py)
