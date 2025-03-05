# scratch.py111
print ('hello word')

a = 100    #赋值
b = 20     #赋值
c = a + b
print (c)

a = 1000
b = 2000
if a > b :
    print(a)
else:
    print(b)

print('  *  ')
print(' ***')
print('*****')

print('      a')
print('    a-b-a')
print('  a-b-c-b-a')
print('a-b-c-d--c-b-a')
print('  a-b-c-b-a')
print('    a-b-a')
print('      a')


print('  * *   * *')
print('*     **     *')
print('*            *')
print('  *        *')
print('      **   ')


a =5                                                     #定义变量a，赋值为5
b =6                                                    #定义变量b，赋值为6
print('a = ',a,',b = ',b)                          #打印a与b的值
print('a - 5 and b < 3 = ', a - 5 and b <3)       #打印a-5 and b< 3的值 ，如果a的值为false（假），无须计算b的值，返回a的值；否则返回b的值
print('a < 6 and b +3 = ', a < 6 and b + 3)      #打印a<6 and b + 3 的值
print('a - 5 or b < 3 = ',a - 5 or b < 3)       #，or或，如果a的值true（真），无须计算b的值，返回a的值，否则返回b的值
print('a < 6 or b + 3 = ', a < 6 or b + 3)
print('not a = ',not a)                               #布尔类型
print(b - a)

int1 = 500                                          #定义变量int1，赋值为500
int2 = 500                                         #定义变量int2,赋值为500
int3 = 520                                        #定义变量int3，赋值为520
print('int1和int2引用的是同一对象？', int1 is int2)
print('int1和int3引用的是同一对象？', int1 is int3)
print('int1的内存地址：',id(int1),'\nint2的内存地址：', id(int2), #各个变量的内存地址
      '\nint3的内存地址：', id(int3))
int1 = 520                                     #修改int1的值为520
print('修改值后的int1和int3引用的是同一对象？', int1 is int3)
print('修改值后的int1内存地址：', id(int1))

a = 2048                             #定义变量a，并赋值为2048
b = 5                                #定义变量b，并赋值为5
print('a的原始值：' ,a)                #输出a
a <<= b                              #将a左移b位，并赋给a
a += b                               #将a加给b，并赋值给a
a *= b                               #将a乘以b，并赋给a
print('a加密后的值：',a)               #输出a
a = a // b                           #将a整除b，并赋给a
a -= b                               #将a减b，并赋值给a
a >>=b                               #将a右移b位，并赋给a
print('a解密后的值：',a)               #输出a

x = input('请输入一个3位自然数')
x = int(x)                      #将输入的数赋值给x
a = x // 100                    #
b = (x // 10)%10
c = x % 10
print(a + b + c)

x = 'joyful'
y = 'for'
s = 'strive to make every day joyful and meaningful ,'\
    'not for others,but for myself'
print(x in s)                                      #真
print(y not in s)                                  #假

a,b,c = 1,2,3
x = (a + c) * b / c
print('x的值：',x)
y = a > b | b > c & c > a
print('y的值:',y)
a = a + b
b = a << 2
c = ~a
print('a的值:',a, '\t','b的值：', b,'\t','c的值: ', c)

sum_num = 0             #初始化一个变量为0
for i in range(1,101):  #for循环遍历1-100所有数字并生成整数序列
    if i % 3 == 0:      #检查当前数字i是否能被3整除，
        sum_num += i    #如果能被3整除就把它加到sum-num上
print(sum_num)          #打印能被3整除的数字

a =  4e2
b = 3e-1
print(a-b)              #399.7

weather = input('请输入')
if weather == '1'or weather =='0':#如果天气为晴或多云
    print('去公园玩')                 #输出
else:
    print('在家玩')

n = int(input('请输入一个整数：'))
i = 1
s = 0
while i <= 0:
    s += i
    i += 1
print('s=1+2+3+...+n=', s)
'''
#使用type函数检查变量的类型
a = 100
b = 123.45
c = 'hello'
d = True
print(type(a))  # int
print(type())
