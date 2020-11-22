# Inheritance
#Please, help me to run this code
class Chef:
    def make_chicken(self):
        print("The chef makes a chicken")
    def make_salad(self):
        print("The chef makes a salad")
    def make_special_dish(self):
        print("The chef makes a special bbq ribs")

myChef = Chef()
myChef.make_chichen()

#My error is as below
'''
Traceback (most recent call last):
    myChef.make_chichen()
AttributeError: 'Chef' object has no attribute 'make_chichen'
'''

