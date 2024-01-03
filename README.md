这是一个hook的PIL.Image的脚本，当被加载后，会重写 PIL.Image.Image 类 和 PIL.Image.open 方法，实现读取图片时解密，保存图片时加密。

如果需要修改密码，修改文件内的变量 _password = '123qwe' 为其他值

通过 import encrypt_image 文件生效
