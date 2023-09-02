class Parent:
    def class1(self):
        print("This is  parent class.")
 
# Derived class
 
 
class Child(Parent):
    def class2(self):
        print("This is  child class.")
 

object = Child()
object.class1()
object.class2()
