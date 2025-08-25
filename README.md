# Experiment-1

# NAME: Dheena Darshini Karthik Dheepan
# REG NO: 212223240030

##  Write programs in Python Language to demonstrate the working of
## following constructs with possible test cases: a) do…while b) while…do c)
## if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Programs:

## a) do…while
~~~
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")

    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)

        while True:
            print(start, end=' ')  # Corrected quote

            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")

display()
~~~

## Output
![Screenshot 2025-03-20 112209](https://github.com/user-attachments/assets/44bfb87e-a0e6-477f-9ac8-30deb173f73e)

![Screenshot 2025-03-20 112220](https://github.com/user-attachments/assets/57a0e702-f03c-4daf-b02e-65c3812638cf)

![Screenshot 2025-03-20 112230](https://github.com/user-attachments/assets/88fcf9c5-924d-410f-9f11-f2e5555ab8f8)

![Screenshot 2025-03-20 112301](https://github.com/user-attachments/assets/2e1b855e-ca61-4d0c-aa1f-53329aca22dd)


## b) while…do
~~~
start = input("Enter a positive value for START: ") 
end = input("Enter a positive value for END: ") 

if start.isnumeric() and end.isnumeric():
    start = int(start)
    end = int(end)

    while start < end:
        print(start)
        start += 1
else:
    print("Enter a valid positive number.")
~~~

## Output
![Screenshot 2025-03-20 112534](https://github.com/user-attachments/assets/f46bb905-71b1-462e-8d2f-83c2e3c45b8b)

![Screenshot 2025-03-20 112558](https://github.com/user-attachments/assets/d084622f-6400-498c-9f26-579da3beabc3)

![Screenshot 2025-03-20 112609](https://github.com/user-attachments/assets/d4185559-98c8-4d11-a031-6cff16cf778c)

![Screenshot 2025-03-20 112617](https://github.com/user-attachments/assets/9e236209-66c8-4155-abad-c60b26eef6ac)


## c) if …else
~~~
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)

        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")

compare()
~~~

## Output

![Screenshot 2025-03-20 114313](https://github.com/user-attachments/assets/14a20364-6fe5-4b41-8e56-9475bb1a5b64)

![Screenshot 2025-03-20 114238](https://github.com/user-attachments/assets/70f7291d-31fe-4553-888e-77c7b4470807)

![Screenshot 2025-03-20 114245](https://github.com/user-attachments/assets/8f03cb07-6fa1-4371-9856-0a77ddd7d319)

![Screenshot 2025-03-20 114303](https://github.com/user-attachments/assets/b46cc633-29f4-440b-bd78-ae3e6212de56)

## d) switch
~~~
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }

    n = input("Enter a value for N: ")
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()

~~~

## Output

![Screenshot 2025-03-22 105112](https://github.com/user-attachments/assets/437e8f6d-c565-4fe7-b395-c90883d9144f)

![Screenshot 2025-03-22 105121](https://github.com/user-attachments/assets/d4d763a7-8629-43a9-be12-8c1c719eaa32)

![Screenshot 2025-03-22 105130](https://github.com/user-attachments/assets/7212d826-f08b-4856-8994-97194ef6650c)

![Screenshot 2025-03-22 105138](https://github.com/user-attachments/assets/1ed5b3dd-95c7-4bdb-8075-1944292ec056)

## e) for
~~~
def iterate():
    string = input("Enter a string: ")  
    for i in string:
        print(ord(i), end=" ")

iterate()
~~~

## Output

![Screenshot 2025-03-22 105828](https://github.com/user-attachments/assets/67619a5e-a2ad-472c-9525-104f05f9054d)

![Screenshot 2025-03-22 105834](https://github.com/user-attachments/assets/8b2a82b2-42cb-4bad-b907-0bc06cfe5480)

![Screenshot 2025-03-22 105841](https://github.com/user-attachments/assets/478c739d-47cf-4159-aa55-9040e6e4e923)




## Result
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully. 




