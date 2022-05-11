# assignment-2-10-05-2022
#COUNT PRIME NUMBERS
def primes(p):
    if p<2:
          return False
    for i in range(2,p):
        if p%i == 0:
            return False
    return True
        
n=int(input())
c=0
for i in range(x):
      if primes(i):
            c+=1
print(c)
