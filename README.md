# Experiment-1
##  Write programs in Python Language to demonstrate the working of
followingconstructs with possible test cases: a) do…while b) while…do c)
if …else d) switch e) for

## a) Aim
To write python programs for do…while, while, for, switch and if…else and test with possible test
cases.

## Algorithm
1.	Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4. Test the program with possible test cases.
5. Stop the program. 

## Program
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        while True:
            print(start, end=' ')
            if start < end:
                start += 1
            else:
                break
    else:
        print("Enter a valid positive number.")
display()


## Output
<img width="326" height="62" alt="Screenshot 2025-08-25 103746" src="https://github.com/user-attachments/assets/589adace-0eaa-45b3-babd-d15fc2433110" />
<img width="348" height="67" alt="Screenshot 2025-08-25 103820" src="https://github.com/user-attachments/assets/9296a969-98de-4126-9eca-bec5cf878fb2" />
<img width="402" height="70" alt="Screenshot 2025-08-25 103845" src="https://github.com/user-attachments/assets/c8034960-60f2-4957-8f64-4330fba1fb21" />
<img width="349" height="76" alt="Screenshot 2025-08-25 103859" src="https://github.com/user-attachments/assets/d3c146c3-0cbf-48d4-a6bd-60b9bf47168d" />



## Result

Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.



