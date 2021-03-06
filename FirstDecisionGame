print("Simple first game build")
print("you will have a health of 10")
print("if health reaches 0 you lose, simple right")

name = input("What is your name:")
age = int(input("What is your age: "))
health = 10
damage = 5 
direction = input("What alley will you choose Right or Left:")

if age >= 18:
    print("Your old enough to play")
else: 
    while age < 18:
            print("Your not old enough to play")
            age = int(input("What is your age:"))


if direction == "right":
    total = health - damage
    print("you went through a lake and a snake bit you, you lose",total, "health")
    print("you have", total, "health left")
    health = 5 
    
lake = input("A cave can be seen in the distance will you go through the cave yes or no:")

if lake == "yes":
    print("With its narrow passages, flowing streams, and chambers studded with stalagmites and stalactites you spot a golden sword")
    decision = input("Do you want to pull the sword out of the ground yes or no:")
if decision == "yes":
    print("the ground start rumbling and rocks starts falling, one of the rocks fell on your head you lose", total,"health")
    health = 0

if health == 0: 
    print("you lose try again")

elif lake == "no":
        print("Mission Fail")
    
elif direction == "left":
        print("you lose try again")
        name = input("What is your name:")
