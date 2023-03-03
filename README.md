# Create-a-Calculator
'''Create a calculator capable of performing addition, subtraction, multiplication, division, modulus, exponential and floor division  operations on two numbers.'''

n1=int(input("Enter first number : "))
n2=int(input("Enter second number : "))

add=n1+n2
print("\nThe addition of two number is : ",add)

sub=n1-n2
print("\nThe subtraction of two number is : ",sub) 

mul=n1*n2
print("\nThe multiplication of two number is : ",mul)

div=n1/n2
print("\nThe division of two number is : ",div)

mod=n1%n2
print("\nThe modulus of two number is : ",mod)

exp=n1**n2
print("\nThe exponential of two number is : ",exp)

f_div=n1//n2
print("\nThe floor division of two number is : ",f_div)
