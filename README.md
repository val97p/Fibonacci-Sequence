# Fibonacci-Sequence
list = [1, 1, 2, 3, 5, 8]


print (list)

#first part

next_number = int(input("what the next number? "))

while next_number != 13:
    next_number = int(input("what the next number? "))

else:
   list.append(next_number)
   print (list)
#ask people if the want to keep playing
continue_question = input("do you want to keep playing? ")

if continue_question == "yes":
    next_number2 = int(input("what the next number? "))

    while next_number2 != 21:
        next_number2 = int(input("what the next number? "))
    else:
        list.append(next_number2)
        print(list)
else:
    print("bye")
# after getting the second number, the program will ask if a player will continue

while continue_question == "yes":
    continue_question2 = input("do you want to keep playing? ")

    if continue_question2 == "yes":
      next_number3 = int(input("what the next number? "))

      while next_number3 != 34:
        next_number3 = int(input("what the next number? "))
      else:
        list.append(next_number3)
        print(list)
    break
else:
    print("bye")

while continue_question2 == "yes":
    continue_question3 = input("do you want to keep playing? ")

    if continue_question3 == "yes":
        next_number4 = int(input("what the next number? "))

        while next_number4 != 55:
            next_number4 = int(input("what the next number? "))
        else:
            list.append(next_number4)
            print(list)
        break
else:
        print("bye")

if continue_question3 == "yes":
    name_question = input("what is the name of this sequence? ")
    while name_question != "fibonacci sequence":
        print("wrong! Try again")
        name_question = input("what is the name of this sequence? ")
    else:
        print("That's right")
else:
    print("bye")

# at this point a player may recognize the sequence
