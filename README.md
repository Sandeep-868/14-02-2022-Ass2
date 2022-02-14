# 14-02-2022-Ass2
Number = int(input(" Enter  Number: "))
Sum = 0

while(Number > 0):
    Reminder = (Number % 10)
    Sum = (Sum + Reminder)
    Number = (Number //10)
print("\n Sum of the digits of Given Number = %d" %Sum)
