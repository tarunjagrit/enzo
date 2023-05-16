# enzo
'''
cars = ['bmw','audi','tesla']
for car in cars:
  if car == 'tesla':
    print(car == "tesla")
'''
requested_topping = ["cheese",'olives',"mushrooms"]
available_topping = ["cheese",'olives','apple']
'mushrooms' in requested_topping
a = input("what toppings you would like to add?\n")
if a in requested_topping:
  print("any other topping you would like to add?")
  b = input("yes / no \n")
  if b == "yes":
    print("your order will be at your door in 30 min. ")
print("thank you")
