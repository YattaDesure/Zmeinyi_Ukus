#1
"""
a = int(input("vvedite a"))
b = int(input("vvedite b"))
print("summa chisel",a + b)
print("вычитание",a - b)
print("умножение",a * b)
print("деление",a / b)
print("остаток",a % b)
print("степень",a ^ b)
print("min=", min(a,b))
print("max=", max(a,b))
"""

#2
"""
a = 4
b = 7
print("%d + %d = %d"  %(a, b , a+b))
print("%d - %d = %d"  %(a, b , a-b))
print("%d * %d = %d"  %(a, b , a*b))
print("%d / %d = %d"  %(a, b , a/b))
"""
#3
"""
import random


a = int(input("vvedite a="))
b = int(input("vvedite b="))
print(random.randint(a,b))
"""

#4
"""
import sys
number = 10


call = int(input("Ввежиет число = "))
print (call, bin(call), oct(call), hex(call))
"""
#5
"""
a = float(input("vvedite a="))
print("{:.3f}".format(a))

N = int(input("Введите количество знаков после запятой для округления: ")) 
rounded_n = round(a, N) 
print(f"Округленное число до {N} знаков: ", rounded_n)
"""
#6
"""
year = int(input("Введите год: "))

is_leap = (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0)
print("Високосный год:", is_leap)
"""
#7
"""
a = int(input("vvedite a="))
b = int(input("vvedite b="))

a, b = b, a

print("After:") 
print("a = ", a) 
print("b = ", b)
"""
#8
"""
n = int(input("n = "))

seconds_in_days = 24 * 60 * 60
n = n % seconds_in_days # days

hours = n // 3600
minutes = (n % 3600) // 60
seconds = n % 60


print(f"{hours:02}:{minutes:02}:{seconds:02}")
"""
