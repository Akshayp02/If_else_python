# If_else_python
# String slice
websitec ="https://www.ggogle.com"
print(websitec[1:4:]) #this is index oparetar

slice = slice(9,-1) #this is a slice Function
print(websitec[slice])

# if Statement : a block of code that will execute if it's condition is true

age =int(input("enter your age"))

if age>=18:
    print("yoy are an adult")
elif age<0:
    print("you haven't the born yet :")
elif age ==100:
    print("you are a century old:")
else:
    print("you are a child")
# logical operator t(and ,or,not) = used to check if two or more conditional statement is true

temp =int(input("what is tempraturee outside ?:"))
if (temp>=0 and temp<= 30):
    print("temprature is good /n go uotside")
elif temp <0 or temp >30:
    print("temprature is bad .....! stay t home ")
# now use the Note = used to check if two or more conditional statement is False 
temp = int(input("what is tempraturee outside ?:"))
if not (temp >= 0 and temp <= 30):
    print("temprature is bad .....! stay t home ")
elif not (temp < 0 or temp > 30):
    print("temprature is good /n go uotside")



