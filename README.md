# CS-112
Sharing programs for class.

def between(num1, num2, num3):
    if (num2 > num1 and num2 < num3) or (num2 <num1 and num2 > num3):
        return 'True'
    else:
        return 'False'
    
while True:
    
    print('Enter first number: ')
    first_num = int(input())
    print('Enter second number: ')
    sec_num = int(input())
    print('Enter third number: ')
    third_num = int(input())

    print('Result is ' + between(first_num, sec_num, third_num))
