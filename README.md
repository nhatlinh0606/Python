# Kiến thức cần nắm
*[Toán tử là gì](https://toidicode.com/cac-toan-tu-co-ban-trong-python-349.html)

*https://codelearn.io/learning/python-fundamentals

# Python
- First program and comments
- Data type, variable and type conversion
- Input
- Basic Operator
- Selection statements 
- Loops
- Array & List
- String 
- Python Function
- Code of practice I
- Code of practice II


## First program and comments

1.Viết chương trình Hello World đầu tiên trong Python 
    
    print("Hello, World!")

2.Bài tập Python cơ bản: tính tổng hai số

    print(5000+555)

3.Bài tập Python cơ bản: tính tổng, hiệu, tích, thương của hai số 

    print("2468 + 1234 =", 2468 + 1234)
    print("2468 - 1234 =", 2468 - 1234)
    print("2468 * 1234 =", 2468 * 1234)
    print("2468 / 1234 =", 2468 / 1234)

4.Bài tập Python cơ bản: tính diện tích hình chữ nhật 

    print("Area =", 6.4 * 7.8)
    print("Perimeter =", (6.4 + 7.8) * 2)

## Data type, variable and type conversion

1.Khai báo biến trong Python 

    # Initialization an integer variable name num_integer
    num_integer = 1000
    # Initialization a float variable name num_float
    num_float = 3.125
    # Initialization a string variable name string_var
    string_var = 'Codelearn.io'
    # Initialization a boolean variable name boolean_var
    boolean_var = True

    #Print value of each variable
    print(num_integer)
    print(num_float)
    print(string_var)
    print(boolean_var)

2.Nối chuỗi và lặp chuỗi trong Python

    name = "Codelearn"
    print("Hello " + name)

3.Bài tập Python cơ bản: nối một chuỗi và một số

Để nối được một chuỗi và một số bạn cần phải đưa được số này về dạng chuỗi. Trong ngôn ngữ lập trình Python bạn có thể dùng hàm str() để làm việc này.

    name = "Codelearn"
    date_of_birth = 2019
    print("Name: " + name)
    print("Date of birth: " + str (date_of_birth))

4.Bài tập python cơ bản: Tính tổng, hiệu, tích, thương của hai số 

    a = 438
    b = 636
    print("a + b = " + str (a + b))
    print("a - b = " + str (a - b))
    print("a * b = " + str (a * b))
    print("a / b = " + str (a / b)) 

5.Bài tập Python cơ bản: tính diện tích và chu vi hình chữ nhật

    length = 7.8
    width = 3.5
    print("Area: " + str (length * width))
    print("Perimeter: " + str ((length + width) * 2))

## Input

1.Nhập xuất dữ liệu cơ bản trong Python

    #input: Abc
    
    name = input()
    print("Hello " + name)

2.Nhập và hiển thị tên và tuổi của một người: int()dạng số nguyên: 4, 5

    #input: Abc,23

    name = input()
    age = int(input())
    print("In 15 years, age of " + name + " will be " + str (age + 15))

3.Toán tử chia lấy phần dư trong Python

    a = int(input())
    b = int(input())
    print("a + b = " + str(a+b))
    print("a - b = " + str(a-b))
    print("a * b = " + str(a*b))
    print("a / b = " + str(a/b))
    print("a % b = " + str(a%b))

4.Hoán đổi giá trị 2 biến

    #input: 1,2

    a = int(input())
    b = int(input())
    c = a
    a = b 
    b = c
    print("after swap a = " + str(a) + ", b = " + str(b))

5.Tính chu vi của một hình tròn: float() dạng số thập phân: 0.1, 1.5 

    u = float(input())
    print("Circumference = " + str( 2 * 3.14 * u))

## Basic Operator

1.Toán tử cơ bản trong Python, tính diện tích hình tam giác

    a = int(input())
    h = int(input())
    area = 1/2 * a * h
    print("The area of triangle is", area)

2.So sánh 2 số trả về kết quả true hoặc false

    x = int(input())
    y = int(input())
    print("x > y:", x > y)

3.In ra giá trị của Total trên từng dòng

    a = int(input())
    Total = int(input())
    Total += a # Using += Operator
    print("The Value of the Total after using += Operator is:", Total)
    Total -= a # Using -= Operator
    print("The Value of the Total after using -= Operator is:", Total)
    Total *= a # Using *= Operator
    print("The Value of the Total after using *= Operator is:", Total)
    Total //= a # Using //= Operator
    print("The Value of the Total after using //= Operator is:", Total)
    Total **= a # Using **= Operator
    print("The Value of the Total after using **= Operator is:", Total)
    Total /= a # Using /= Operator
    print("The Value of the Total after using /= Operator is:", Total)
    Total %= a # Using %= Operator
    print("The Value of the Total after using %= Operator is:", Total)

4.Kiểm xem một giá trị có nằm trong giá trị khác hay không (Toán Tử khai thác)

    x = input()
    print('H' in x)

*   **in**	Nếu 1 đối số thuộc một tập đối số nó sẽ trả về True và ngược lại/	a in b //False

*   **not in**	Nếu 1 đối số không thuộc một tập đối số nó sẽ trả về True và ngược lại/	a not in b //True

5.Toán tử định danh Identity trong Python (toán tử xác thực)

    a = int(input())
    b = int(input())
    print(a is b)

*   **is**	Toán tử này sẽ trả về True nếu a == b và ngược lại	 a is b //False
*   **not is**	Toán tử này sẽ trả về True nếu a != b và ngược lại	a is not b //True

6.Toán tử Logical trong Python (toán tử  logic)

    x = int(input())
    y = int(input())
    z = int(input())
    t = int(input())
    print("Result evaluation is", (x > y) and (z < t))

*   **and**	Nếu 2 vế của toán tử này đều là True thì kết quả sẽ là True và ngược lại nếu 1 trong 2 vế là False thì kết quả trả về sẽ là False.
*   **or**	Nếu 1 trong 2 vế là True thì kết quả trả về sẽ là True và ngược lại nếu cả 2 vế là False thì kết quả trả về sẽ là False.
*   **not**	Đây là dạng phủ định, nếu biểu thức là True thì nó sẽ trả về là False và ngược lại.

## Selection statements

26.Câu lệnh if-else trong Python

    a = int(input())
    print ("Your cat is young") if a < 5 else print ("Your cat is old")

27.Rút gọn mệnh đề if-else thành elif trong Python

    a = int(input())
    if a >= 100:
        print ("Stay at home and enjoy a good movie")
    elif a >= 92:
        print ("Stay at home")
    elif a == 75:
        print("Go outside and enjoy the weather")
    elif a <= 0:
        print("It's cool outside")
    else:
        print("Let's go to school")

28.Tính trung bình của 3 số tự nhiên

    a = int(input())
    b = int(input())
    c = int(input())
    avg = (a + b + c) /3

    if avg > a and avg > b: print("The average value is greater than both a and b")
    elif avg >a and avg >c: print("The average value is greater than both a and c")
    elif avg >b and avg >c: print("The average value is greater than both b and c")
    elif avg >a: print("The average value is greater than a")
    elif avg >b: print("The average value is greater than b")
    elif avg >c: print("The average value is greater than c")

29.In ra màn hình so sánh năm tuổi của vật nuôi

    a = int(input())
    if a <= 0: print("This can hardly be true")
    elif a == 1: print("About 1 human year")
    elif a == 2: print("About 2 human years")
    elif a > 2: print("Over 5 human years")

    
