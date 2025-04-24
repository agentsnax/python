#prime numbers using for loop
for i in range(2,100):
	for j in range(2,i):
		if i%j==0:
			break
	else:
		print(i,end=" ")
*********************************************
# Print numbers from 1 to 10 using a for loop

for i in range(1, 11):
    print(i)
*********************************************
# Print odd numbers from 1 to a given limit using a for loop

limit = int(input("Enter the upper limit: "))

print("Odd numbers up to", limit, "are:")

for i in range(1, limit + 1, 2):  # Start at 1, step by 2
    print(i)



*********************************************
# Print numbers from 1 to 10 using a while loop

i = 1  # starting value

while i <= 10:
    print(i)
    i += 1  # increment by 1
**********************************************
# Program to print prime numbers up to a given limit using a while loop

limit = int(input("Enter the upper limit: "))

num = 2  # Starting from the first prime number

print("Prime numbers up to", limit, "are:")

while num <= limit:
    is_prime = True
    i = 2
    while i <= num // 2:
        if num % i == 0:
            is_prime = False
            break
        i += 1
    if is_prime:
        print(num)
    num += 1
*********************************************
# Print even numbers from 1 to a given limit using a while loop

limit = int(input("Enter the upper limit: "))

num = 2  # Start from the first even number

print("Even numbers up to", limit, "are:")

while num <= limit:
    print(num)
    num += 2  # Increment by 2 to get the next even number



























