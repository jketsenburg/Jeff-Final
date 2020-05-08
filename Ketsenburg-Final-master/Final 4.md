# Past Work
<p> Here is some of my past work while in this class, it is code to get a calculator to work properly.</p>
    

    #This function adds two numbers
    def add(x,y):
        return x + y
    
    #This function subtracts two numbers
    def subtract(x,y):
        return x - y
    
    #This function multiplys two numbers
    def multiply(x,y):
        return x * y
    
    #This function divides two numbers
    def divide(x,y):
        return x / y
    
    def main(): #
    
        while (True):
    
                print("Select Operation.")
                print("1. Add")
                print("2. Subtract")
                print("3. Multiply")
                print("4. Divide")
    
                #Take the input from  the user
           
                choice = input("Enter choice(1/2/3/4): ")
    
                    
    
                num1 = float(input("Enter first number: "))
                num2 = float(input("Enter second number: "))
    
                if choice == '1':
                    print(num1,"+",num2,"=", add(num1,num2))
    
                elif choice == '2':
                    print(num1,"-",num2,"=", subtract(num1,num2))
    
                elif choice == '3':
                    print(num1,"*",num2,"=", multiply(num1,num2))
    
                elif choice == '4':
                    print(num1,"/",num2,"=", divide(num1, num2))
    
                else:
                    print("Invalid input, please retry.")
    
                do_again = input("Press 'y' to enter another calculation. Press any other key to end the program.")
    
                if do_again != "y":
                    break
    
    main()
    

 

 `       
     [Main Page](https://github.com/jketsenburg/Jeff-Final/blob/master/Ketsenburg-Final-master/Final.md)
