# davaleba
davaleba_4
N1
# 1
class people:
    def __init__(self, firstname, lastname, ):
        self.firstname = firstname
        self.lastname = lastname

    def print_lastname(self):
        print(self.lastname)

    def print_firstname(self):
        print(self.firstname)


class Triangle(people):
    pass


p1 = people("lizi", "bukhrashvili")
p1.print_firstname()
p1.print_lastname()
t1 = Triangle("lizz", "bukhra")
t1.print_firstname()
t1.print_lastname()


# 2
class lecturer:
    def __init__(self, firstname, lastname, salary):
        self.firstname = firstname
        self.lastname = lastname
        self.salary = salary

    def print_lastname(self):
        print(self.lastname)

    def print_firstname(self):
        print(self.firstname)

    def print_salary(self):
        print(self.salary)

class Triangle(lecturer):
    pass


l1 = lecturer("nini", "kvinikadze", 10000)
l1.print_firstname()
l1.print_lastname()
l1.print_salary()
t1 = Triangle("nino", "kvini", 5000)
t1.print_lastname()
t1.print_firstname()
t1.print_salary()


# 3
class student:
    def __init__(self, firstname, lastname, courses):
        self.firstname = firstname
        self.lastname = lastname
        self.courses = courses

    def print_lastname(self):
        print(self.lastname)

    def print_firstname(self):
        print(self.firstname)

    def print_courses(self):
        print(self.courses)


class Triangle(student):
    pass


s1 = student("liziko", "bukhara", 2 )
s1.print_firstname()
s1.print_lastname()
s1.print_courses()
t1 = Triangle("liz", "bukh", 4 )
t1.print_firstname()
t1.print_lastname()
t1.print_courses()


# N2

class Libraryltem:
    def __init__(self, title, subject, status):
        self.title = title
        self.subject = subject
        self.status = status

    def print_title(self):
        print(self.title)

    def print_subject(self):
        print(self.subject)

    def print_status(self):
        print(self.status)

class Triangle(Libraryltem):
    pass


l1 = Libraryltem("Kvavili", "Art", "aviable")
l1.print_title()
l1.print_subject()
l1.print_status()
t1 = Triangle("flower", "English", "aviable")
t1.print_title()
t1.print_subject()
t1.print_status()
