以后用来记录学习的内容
![download](https://user-images.githubusercontent.com/62737747/180129280-6e525d59-beba-479a-8c38-560743db519b.png)
ASCII 转成 二进制 再转成 base64 再转成 二进制 再转成  utf-8？
内容本质上都是以二级制存的吧
btoa('name')  base64转成ASCII码  字符串为啥是二进制数据？
atob( )       ASCII码转成base64
所以任何数据都可以通过JSON.stringfy() 转成字符串，然后再转成base64？