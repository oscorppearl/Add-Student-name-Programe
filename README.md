# Add-Student-name-Programe !# Python
this program is to add Students name and give list of Students in the List

please Help to print the List of All students added at the end of the Programe


students = []


def get_student_titlecase():
    students_titlecase = []
    for student in students:
        students_titlecase = student["name"].title()
    return students_titlecase


def print_student_titlecase():
    students_titlecase = get_student_titlecase()
    print("student name is =>", students_titlecase, ";", "Student ID is =>", student_id)


def add_student(name, student_id=999):
    student = {"name": name, "student_id": student_id}
    students.append(student)


student_list = get_student_titlecase()

student_list = get_student_titlecase()
student_name = input("Enter Student name: ")
student_id = input("Enter Student ID: ")

add_student(student_name, student_id)
print_student_titlecase()


while True:
    reply = input("do you wish to continue entering Data: ")
    if reply == "No": break
    print("Keep Entering")


    student_list = get_student_titlecase()
    student_name = input("Enter Student name: ")
    student_id = input("Enter Student ID: ")

    add_student(student_name, student_id)
    print_student_titlecase()





