# 

## Задание 1 Создайте функцию , которая прнимает в качестве аргументов два числа и возвращает их сумму.
    def function():
    a = int(input("Введите первый аргумент"))
    b = int(input("Введите второй аргумент"))
    c = a + b
    print(c)
    function()
   
  ## Задание 2. Создайте фунцию , которая принимает список чисел в качестве аргументов и возвращает наибольшее число в списке.
    def function():
    list = []
    a = 5
    for i in range(a):
    x = int(input())
    list.append(x)
    print(max(list))  
    function()

## Задание 3 Создайте фунцию , которая принимает строку в качестве аргумента и возвращает количетсво гласных в строке
    def function():
    count = 0
    list = input()
    for i in "ауеюэияо":
    count += list.count(i)
    print(count)
    function()
    
## Задание 4  
    def function():
    list1 = input()
    list2 = input()
    text = ''.join(reversed(list2))  #join(), объединяющий все символы, полученные в результате обратной итерации в новой строке.
    if list1 == text:
        print("TRUE")
    else:
        print("FALSE")
function()

 ## Задание 5
    def function():
    str1 = input()
    str2 = input()
    if str1 in str2:
        print("TRUE")
    elif str2 in str1:
        print("TRUE")
    else:
        print("FALSE")
       function()
       
  ## Задание 6
    def function():
    list1 = input()
    list2 = input()
    text = ''.join(reversed(list2))  #join(), объединяющий все символы, полученные в результате обратной итерации в новой строке.
    if list1 == text:
        print("TRUE")
    else:
        print("FALSE")
    function()
     
      
  ## Задание 7
    def function():
    a = int(input())
    b = int(input())
    c = int(input())
    if a > b and a > c:
        print("TRUE")
    elif b > a and b > c:
        print("TRUE")
    elif c > a and c > b:
        print("TRUE")
    else:
        print("FALSE")
function()


   ## Задание 8
    def function():
    a = int(input())
    b = int(input())
    c = int(input())
    if a == b or a == c:
        print("TRUE")
    elif b == a or b == c:
        print("TRUE")
    elif c == a or c == b:
        print("TRUE")
    else:
        print("FALSE")
function()


   ## Задание 9
    def function():
    str1 = input()
    str2 = input()
    str3 = input()
    if len(str1) > len(str2+str3):
        print("TRUE")
    elif len(str2) > len(str1+str3):
        print("TRUE")
    elif len(str3) > len(str2+str1):
        print("TRUE")
    else:
        print("FALSE")
  function()
  
  ## Задание 10
    def function():
    str1 = input()
    str2 = input()
    str3 = input()
    if len(str1) == len(str2) or len(str1) == len(str3):
        print("TRUE")
    elif len(str2) == len(str1) or len(str2) == len(str3):
        print("TRUE")
    elif len(str3) == len(str2) or len(str1) == len(str3):
        print("TRUE")
    else:
        print("FALSE")
function()
    
    
    
   ## Задание 11
     def function():
    str1 = input()
    str2 = input()
    if str1 == str2:
        print("TRUE")
    else:
        print("FALSE")
   function()
   
   ## Задание 12
   
     def function():
     a = input()
     b = input()
     c = 0
     for i in a:
        c = с * i
     for z in b:
        c = c * z
     print(c)
     function()

   
   ## Задание 14
     def function():
    list = []
    str1 = input()
    str2 = input()
    list.append(str1 + str2)
    print(list)
function()


   ## Задание 15 
     def function():
    a = {1:'peanut', 2:'butter', 3:'jelly', 4:'time'}
    b = {5:'fish', 6:'chips'} 
    x = a|b
    print(x)
function()

  ## Задание 16
    def factorial(number):
    if number == 1:
        return number
    else:
        return number * factorial(number - 1)
        print(factorial(int(input('Введите число: '))))


  ## Задание 17
    
    
    
    def function():
    l = input()
    for i in l:
        print(i)
function()



  ## Задание 18
    
    def function():
    a = []
    n = int(input())
    for i in range(n):
        x = int(input())
        a.append(x)
    for z in a:
        print(z)
function()
     
