# Student-result-calculator-
A beginner Python project to calculate student results and percentage🧿
name = input("Enter student name: ")
m1 = int(input("Enter Math marks: "))
m2 = int(input("Enter Science marks: "))
m3 = int(input("Enter English marks: "))

total = m1 + m2 + m3
percentage = total / 3

print("\n--- RESULT ---")
print("Student Name:", name)
print("Total Marks:", total)
print("Percentage:", percentage)

if percentage >= 60:
    print("Division: First")
elif percentage >= 40:
    print("Division: Pass")
else:
    print("Division: Fail")