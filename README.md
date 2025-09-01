student_marks = {
    "Alice": 85,
    "Bob": 92,
    "Charlie": 78
}

# Ask for student name
name = input("Enter the student's name: ")

# Check and print result
if name in student_marks:
    print(f"{name}'s marks: {student_marks[name]}")
else:
    print("Student not found.")
