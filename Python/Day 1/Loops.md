For Loop
n = int(input("Enter a number: "))
for i in range(n):
    print(i)


While Loop
m = int(input("Enter a number: "))
i = 0
while i < m:
    print(i)
    i += 1


#match case
day = int(input("Enter a day of the week: "))
match day:
    case 1:
        print("Monday")
    case 2:
        print("Tuesday")
    case 3:
        print("Wednesday")
    case 4:
        print("Thursday")
    case 5:
        print("Friday")
    case 6:
        print("Saturday")
    case 7:
        print("Sunday")
    case _:
        print("Invalid day of the week.")
