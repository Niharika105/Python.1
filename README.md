class Student:
    def __init__(self,roll_no,name,address,course):
        self.roll_no = roll_no
        self.name = name
        self.address = address
        self.course = course
    def print_details(self):
        print(f"Roll No:{self.roll_no}")
        print(f"Name:{self.name}")
        print(f"Address:{self.address}")
        print(f"course:{self.course}")
student1 = Student(101,"Alice","123 main st","computer science")
student1.print_details()
