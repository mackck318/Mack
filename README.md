# Mack
python


# num = int(input("请输入你想知道的数判断是否为偶数:"))
# if num % 2 == 0:
#     print("这是一个偶数")
# else:
#     print("这不是偶  数")

#判断两个数哪个大
#a和b利用比较运算符
#如果a小于b 则打印b
#否则说明a大于b ，打印a
# a = float(input("请输入您下比较的数:"))
# b = float(input("请输入您下比较的数:"))
#
# if a <= b :
#     print("%.2f小于等于%.2f" %(a,b))
# else :
#     print("%.2f大于%.2f" %(a,b))

#
# input_un = input("请输入您账号:")
# input_pw = input("请输入您密码:")
#
# if input_un=="123456" and input_pw=="654321":
#     print("登陆成功")
# else :
#     print("验证错误，登陆失败")

#
# #让用户输入星期几
# week = int (input("请输入今天是星期几用数字1-7表示:"))
# if week == 1:
#     print("跑步")
# elif week == 2:
#     print("踢球")
# elif week == 3:
#     print("健身房")
# elif week == 4:
#     print("拳击")
# elif week == 5:
#     print("游泳")
# elif week == 6:
#     print("散步")
# elif week == 7:
#     print("大吃一顿")
# else :
#     print("对不起没有对应的星期")


#判断这个数是奇数还是偶数，还是负数
x = float(input("请输入您下测试的数字:"))
#判断是正负数
if x >= 0 :
    #判断是不是偶数
    if x % 2 == 0 :
        print("这是个偶数")
    else :
        print("这是个奇数")
#不是正数则是负数
else :
    print("这是个负数")
    
    
    
    # a = 5
# # print(type(a))
# #
# # b = 1.5
# # print(type(b))
# #
# # c="123"
# # print(type(c))
# #
# # d = False
# # print(type(d))



print( True and False )
print( True or False )
print( not False )
print(10>5 and 10<11)



#需要求圆的面积
#要求输入任意数字都可以计算
#结果需要用详细语句输出
#已知圆的pi
pi = 3.14
#输入半径
r = float(input("请输入您需要计算圆的半径:"))
#圆面积公式
area = pi * r **2
print("您输入的半径是%.2f，圆周率精确到%.2f，计算出的圆面积是%.2f：" % (r,pi,area))



# 外卖结算 30-10 ，50-20 ， 100-50， 会员打八折
# 设置变量并让输出金额
# 设置变量的if有几种情况
price = float(input("请输入你外卖的价格:"))
member = input("您是否是会员(是或否):")

if price >= 100:
    price -= 50
elif price >= 50 and price < 100:
    price -= 20
elif price >= 30 and price < 50:
    price -= 10
else:
    price == price
if member == "是":
    price *= 0.8

print("您的最终外卖价格是%.2f元。" % price)



# #输入三个数字，找出最大的数
# #三个数比较可以先比较2个数，大的数再和第三个数比较
# #设三个数是abc，假设a>b，让a和C进行比较
# #否则B大，让b和C进行比较
# a = int(input("请输入一个数:"))
# b = int(input("请输入一个数:"))
# c = int(input("请输入一个数:"))
#
# if a > b :
#     if a > c :
#         print(a)
#     else :
#         print(c)
# else :
#     if b > c :
#         print(b)
#     else:
#         print(c)


a = 15
if a <10 :
    print("小于10")
elif a <= 15:
     print("大于10小于等于15")
elif a == 15:
     print("等于15")
else:
     print("大于15")

# 提示用户输入一个大于100 小于999 的数字，然后打印个位，十位，百位。
# 大于100 小于999  相当于100< x < 999
# 让用户输入一个三位数
# 分别显示三位数，百位是整除100，十位数是除100的余数整除10，个位数是整除10 的余数
x = int(input("请输入一个三位数:"))
if x<999 and x>100 :
    print()
    a = x // 100
    b = x % 100 // 10
    c = x % 10
    print("您输入的数字为:%d,百位：%d ，十位：%d ,个数：%d" % (x, a, b, c))
else :
    print("您输入的不是三位数")
# 考试成绩的问题：提示用户输入成绩，判断是属于哪个水平，将结果打印到控制台。
# 60以下不及格，60分以上为及格，70分至80分为合格，80分至90分为良好，90分以上为优秀。
x = float(input("请输入你的成绩:"))
if x > 90:
    print("优秀")
elif  x >=80:
    print("良好")
elif x >= 70:
    print("合格")
elif x >= 60:
    print("及格")
else:
    print("不及格")



# a = 5
# a += 10
# print(a)
#
# b = 5
# b -= 10
# print(b)

#a=haha
a = "haha"
#让haha加上hehe
a += "hehe"
#打印
print(a)


#把haha打印10遍
b = "haha"
b *= 10
print(b)




# age = input("请输入您的年龄:")
# print(age)


# #计算两个数的乘积，数字通过键盘输入
# # a = float(input("请输入你需要计算的数字:"))
# # b = float(input("请输入你需要计算的数字:"))
# # print(a*b)


