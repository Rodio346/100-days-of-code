### Solutions ###


**Python if else** https://www.hackerrank.com/challenges/py-if-else/problem
## Solution ##
if __name__ == '__main__':
    n = int(input().strip())
    if (n%2==1) or (n>=6 and n<=20 and n%2==0):
        print("Weird")
    elif (n%2==0) and ((n>=2 and n<=5) or n>20):
        print("Not Weird")

**Arithmetic Operators** https://www.hackerrank.com/challenges/python-arithmetic-operators/problem
## Solution ##