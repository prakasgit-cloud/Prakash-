# calculator with while loop
while True:
    print("\n--- नया कैलकुलेशन ---")
    
    # यूजर से पूछें कि क्या आगे बढ़ना है या बंद करना है
    control = input("क्या आप कैलकुलेशन करना चाहते हैं? (y/n): ")
    if control.lower() == 'n':
        print("प्रोग्राम बंद हो रहा है। बाय!")
        break  # लूप से बाहर आने के लिए
        
    a = float(input("Enter the 1st num: "))
    b = float(input("Enter the 2nd num: "))
    op = input("Enter operator (+, -, *, /, %, **): ")

    if op == "+":
        print("Result:", a + b)
    elif op == "-":
        print("Result:", a - b)
    elif op == "*":
        print("Result:", a * b)
    elif op == "/":
        print("Result:", a / b)
    elif op == "%":
        print("Result:", a % b)
    elif op == "**":
        print("Result:", a ** b)
    else:
        print("Niter Biler")
        
