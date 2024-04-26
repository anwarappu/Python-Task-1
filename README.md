# Python-Task-1

#FIND THE NUMBERS WHICH ARE DIVISIBLE BY 7 AND MULTIPLES OF 5

a=int(input("enter the start number: "))
b=int(input("enter the end number"))

for number in range(a,b + 1):
  if (number % 7 == 0 and number % 5 == 0):
    print(f'The number {number} is divisible by 7 and multiple of 5')
