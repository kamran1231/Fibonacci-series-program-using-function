# Fibonacci-series-program-using-function


def fibonacci_number(num):
    a = 0
    b = 1

    if num == 0:
        print('enter the number greater than 0')


    elif num == 1:
        print(a)

    elif num == 2:
        print(a,b)

    else:
        print(a,b,end = ' ')

        for i in range(num-2):
            c = a + b
            a = b
            b = c
            print(b,end= ' ')


fibonacci_number(num = int(input('enter the number: ')))
