# 


     #Задание 1
    def function():
    a = int(input("Введите первый аргумент"))
    b = int(input("Введите второй аргумент"))
    c = a + b
    print(c)
    function()
    
    
    
    #Задание 2.
    def function():
    list = []
    a = 5
    for i in range(a):
    x = int(input())
    list.append(x)
    print(max(list))  
    function()


    #Задание 3
    def function():
    count = 0
    list = input()
    for i in "ауеюэияо":
    count += list.count(i)
    print(count)
    function()
    
    #Задание 4
    def function():
    list1 = input()
    list2 = input()
    text = ''.join(reversed(list2))  #join(), объединяющий все символы, полученные в результате обратной итерации в новой строке.
    if list1 == text:
        print("TRUE")
    else:
        print("FALSE")
function()

    #Задание 5
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
