# HowToFindPrimeNumbers

num = int(input("Find Prime Numbers"))

if (num == 2):
    print("%d is a prime number" % (num))
else:
    for i in range(2, num):
        if (num % i == 0):
            print("%d isn't a prime number" % (num))
            break
    else:
        print("%d is a prime number" % (num))
