# EasyCalc
```
def add(x, y):  
    return x + y  

def subtract(x, y):  
    return x - y  

def multiply(x, y):  
    return x * y  

def divide(x, y):  
    if y != 0:  
        return x / y  
    else:  
        return "Cannot divide by zero!"  

def calculator():  
    print("Select operation:")  
    print("1. Add")  
    print("2. Subtract")  
    print("3. Multiply")  
    print("4. Divide")  

    while True:  
        choice = input("Enter choice (1/2/3/4) or 'exit' to quit: ")  

        if choice == 'exit':  
            print("Exiting the program...")  
            break  

        if choice in ['1', '2', '3', '4']:  
            num1 = float(input("Enter first number: "))  
            num2 = float(input("Enter second number: "))  

            if choice == '1':  
                print(f"{num1} + {num2} = {add(num1, num2)}")  
            elif choice == '2':  
                print(f"{num1} - {num2} = {subtract(num1, num2)}")  
            elif choice == '3':  
                print(f"{num1} * {num2} = {multiply(num1, num2)}")  
            elif choice == '4':  
                print(f"{num1} / {num2} = {divide(num1, num2)}")  
        else:  
            print("Invalid choice!")  

if __name__ == "__main__":  
    calculator()
```

همچنین میتوانید با نصب برنامه گیت پروژه را در کامپیوتر خود کلون کنید.

ا1_بتدا مطمعن شوید برنامه git روی لپتاپ شما نصب است. ( [وبسایت رسمی](https://git-scm.com/downloads)  )
2_ سپس محیط cmd کامپیوتر را باز کنید و دستورات زیر را بنویسید.
```
git clone https://github.com/arshiakia/EasyCalc.git
```
```
cd EasyCalc
```
```
pip install -r requirements.txt
```
```
python EasyCalc.py
```

توضیح ماشین حساب ( EasyCalc )
 
این ماشین حساب ساده با استفاده از زبان برنامه‌نویسی پایتون طراحی شده است تا کاربران بتوانند به راحتی محاسبات ریاضی خود را انجام دهند. این برنامه به‌طور ویژه برای کاربرانی که به دنبال ابزاری سریع و کارآمد برای انجام عملیات پایه‌ای ریاضی هستند، مناسب است. 

ویژگی‌های کلیدی ماشین حساب:

1. عملیات پایه: ماشین حساب قابلیت انجام چهار عمل اصلی ریاضی: جمع، تفریق، ضرب و تقسیم را دارد. کاربران می‌توانند با وارد کردن دو عدد و انتخاب نوع عمل، نتیجه را به سرعت دریافت کنند.

2. راحتی در استفاده: این برنامه به گونه‌ای طراحی شده است که کاربر به سادگی می‌تواند گزینه مورد نظر خود را انتخاب کند و وارد کردن اعداد نیز به سادگی انجام می‌شود. 

3. مدیریت خطا: یکی از ویژگی‌های مهم این ماشین حساب، مدیریت خطاهاست. به‌عنوان مثال، در صورت تلاش برای تقسیم بر صفر، برنامه پیام مناسب را به کاربر نمایش می‌دهد.

4. قابلیت خروج: برنامه به کاربران این امکان را می‌دهد که با وارد کردن کلمه «exit» از برنامه خارج شوند. این ویژگی تجربه کاربری را بهبود می‌بخشد و از گیج شدن کاربر جلوگیری می‌کند.





Calculator Description

This simple calculator has been designed using the Python programming language to allow users to easily perform their mathematical calculations. This program is particularly suitable for users seeking a quick and efficient tool for basic arithmetic operations.

Key Features of the Calculator:

1. Basic Operations: The calculator is capable of performing four main arithmetic operations: addition, subtraction, multiplication, and division. Users can quickly obtain results by entering two numbers and selecting the desired operation.

2. Ease of Use: The program is designed in such a way that users can easily select their desired option and input numbers without complications.

3. Error Handling: One of the important features of this calculator is its error management. For example, if a user attempts to divide by zero, the program displays an appropriate message to the user.

4. Exit Capability: The program allows users to exit by entering the command "exit." This feature enhances the user experience and prevents confusion.


