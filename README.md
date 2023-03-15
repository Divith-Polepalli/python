def sum(a, b):
    return (a + b)
a = int(input('Enter number of children: '))
b = int(input('Enter the amount you make NOTE: NUMBER MUST BE AQURATE TO THE DOLLAR!!!!:'))
print (f'**YOU GET 20 PER CHILD WHICH IS:**')
print (a*20) 
a = (a*20)
if a > 20:
  print('You are not elgible') 

b = (b/10)
if a  < 75000:
   print(f'You get {a} and {b}  which is {sum(a, b)}')
