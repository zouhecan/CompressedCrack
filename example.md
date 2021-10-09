全字符校验，不指定密码长度：
python3 crack.py -i test1.zip'-

全字符校验，指定密码长度最小为4，最大为6
python3 crack.py -i chou.zip 4 6 

指定校验字符集为数字和小写字母，指定密码长度最小为4，最大为6

[comment]: <> (python3 crack.py -i chou.zip 4 6 abcdefghijklmnopqrstuvwxyz0123456789)
python3 crack.py -i test.zip 4 4 0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ
