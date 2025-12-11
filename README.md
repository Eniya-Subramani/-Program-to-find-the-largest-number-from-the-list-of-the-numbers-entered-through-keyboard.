n=int(input("Enter the limit less than 99999999999 "))
small=99999999999
for i in range(1,n+1):
  print("Enter ",i,end='')
  a=int(input("th number: "))
  if a<small:
    small=a
print("Smallest no. is: ",small)

OUTPUT:

Enter the limit less than 99999999999 5
Enter  1th number: 24
Enter  2th number: 34
Enter  3th number: 12
Enter  4th number: 11
Enter  5th number: 32
Smallest no. is:  11
