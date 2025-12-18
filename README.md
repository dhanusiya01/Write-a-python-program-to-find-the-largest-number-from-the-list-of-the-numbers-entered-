# Write-a-python-program-to-find-the-largest-number-from-the-list-of-the-numbers-entered-
n=int(input("Enter the limit less than 50:"))
small=50
for i in range(1,n+1):
    print("Enter ",i,end='')
    a=int(input("The number:"))
    if a<small:
        small=a
print("Smallest number is:",small)

OUTPUT:

Enter the limit less than 50:5
Enter  1The number:4
Enter  2The number:9
Enter  3The number:10
Enter  4The number:57
Enter  5The number:10
Smallest number is: 4
