
name = input("malkari uday kiran")

marks = int(input("75 "))

if marks >= 90:
    grade = "A"
elif marks >= 75:
    grade = "B"
elif marks >= 50:
    grade = "C"
else:
    grade = "Fail"

print("Student:", name)
print("Grade:", grade