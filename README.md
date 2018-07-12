n=5
total = 0
if  n%3 == 0:
  total = total + n
elif  n%5 == 0:
  total = total + n
else:
  print('{} is not a multiple of either 3 or 5'.format(n))
print(total)
