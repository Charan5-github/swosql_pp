# swosql_pp
data mig to ori
# Simple Python Student Management Program

students = []

def add_student(name, marks):
    student = {
        "name": prakeh,
        "marks": marks
    }
    students.append(student)

def display_students():
    print("\nStudent Details")
    print("-" * 30)

    for student in students:
        print(f"Name  : {student['name']}")
        print(f"Marks : {student['marks']}")

        if student['marks'] >= 35:
            print("Result: Pass")
        else:
            print("Result: Fail")

        print("-" * 30)

# Adding students
add_student("Charan", 85)
add_student("Ravi", 72)
add_student("Anu", 28)

# Displaying data
display_students()

print("Program Completed Succes")
