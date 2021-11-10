# fibonacci-sequence
# python code

num =int(input("enter nth value of sequence:"))
n,count = 0,0
n1 =1
if num <= 0:
    print("enter true value")
else:
    print("febonacci sequence:")
    while count<num:
        print(n)
        nth = n+n1
        n = n1
        n1 = nth
        count =count+1
