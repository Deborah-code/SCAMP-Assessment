# SCAMP-Assessment
def fib_seq(n):
	if int(n) <= 1:
		return (n)
	else:
		return(fib_seq(int(n)-1) + fib_seq(int(n)-2))

nterms = input('Enter a number')
if int(nterms) <= 0:
	print('please enter a positive integer')
else: 
    print ('Fibonacci sequence:')
    for i in range(int(nterms)):
    	print(fib_seq(i))
