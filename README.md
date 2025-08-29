# student-grade-calculator
A simple Python project to calculate total marks, percentage, and pass/fail result of a student based on subject-wise marks input. Includes detailed progress report generation.


#student grade calculation
print("-----STUDENT DETAILS-----")

stname = input("Enter name of student: ")
stfather = input("Enter name of father: ")
stclass = input("Enter class & section: ")
stgen = input("Enter gender: ")
styear = input("Enter session: ")
stno = input("st admission no: ")
print("\n")

#subject marks details
print("-----SUBJECT DETAILS-----")
sub1 = input("Enter sub1: ")
credit1 = float(input("marks1: "))

sub2 = input("Enter sub2: ")
credit2 = float(input("marks2: "))

sub3 = input("Enter sub3: ")
credit3 = float(input("marks3: "))

sub4 = input("Enter sub4: ")
credit4 = float(input("marks4: "))

sub5 = input("Enter sub5: ")
credit5 = float(input("marks5: "))

sub6 = input("Enter sub6: ")
credit6 = float(input("marks6: "))

Total = credit1+ credit2 + credit3 + credit4 + credit5 + credit6
print("\n")

#school details
print("Nation College of Science. Bangalore,Rajajinagar,karnataka\n")

#student information
print(" -----STUDENT DETAILS-----")
print(f"Student name:  {stname}          Gender: {stgen}")
print(f"Father name: {stfather}            Session: {styear}")
print(f"Class&Section: {stclass}          Admn No: {stno}")
print("\n")

#subject details
print("--PROGRESS REPORT OF QUARTERLY EXAM--")

print("(1)", sub1)
print("Marks: ", credit1)
print("\n")

print("(2)", sub2)
print("Marks: ", credit2)
print("\n")

print("(3)", sub3)
print("Marks: ", credit3)
print("\n")

print("(4)", sub4)
print("Marks: ", credit4)
print("\n")

print("(5)", sub5)
print("Marks: ", credit5)
print("\n")

print("(6)", sub6)
print("Marks: ", credit6)

print("----------------------------------------")

#calculation
print("TOTAL MARKS:  ", Total)
print("----------------------------------------")
PERCENTAGE = Total * 100 / 600

print("PERCENTAGE: ", PERCENTAGE)

if (credit1 < 36 or credit2 <36 or credit3 < 36 or credit4 < 36 or credit5 < 36 or credit6 < 36 ):
print("FAIL")

elif PERCENTAGE >= 36:
print("PASS")

else:
print("FAIL")

print("----------------------------------------")

