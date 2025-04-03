# ACTIVITYYYYY

class Dog:
    def speak(self):
        return "woof"
    
class Cat:
    def speak(self):
        return "meow"
    
animals = [Dog(),Cat()]

for animal in animals:
    print(animal.speak())
    

def add(a,b,c=0):
    return a + b + c

print(add(2,3))
print(add(2,3,4))




class Bird:
    def fly(self):
        return "Some birds can fly."
    
class Sparrow(Bird):
    def fly(self):
        return "Sparrow flies fast."
    
class Penguin(Bird):
    def fly(self):
        return "Penguins cannot fly."
    
bird = [Bird(), Sparrow(), Penguin()]
for bird in bird:
    print(bird.fly())
