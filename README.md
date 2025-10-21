import math
print("The value of pi is",math.pi)     
class Student:
    def __init__(self, nm, ID,spec):
        self.name =nm
        self.ID = ID
        self.specialization=spec
    def persontaling(self):
        print("my name is:"  +  self.name + ", and my ID is:" +str(self.ID) + ", and my specialization is:" +self.specialization)   
lujain = Student("Lujain", 20248888, "Cybersecrity.")
print(lujain.name, lujain.ID, lujain.specialization )
lujain.persontaling()
