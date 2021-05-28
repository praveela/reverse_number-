# reverse_number

num=int(input()) 
rev=0
While(num>0) 
     rem=num%10 #finding remainder
     rev=(rev*10) +rem
     num=num//10 # finding quotient
Print("%d" %rev) 
 
Input:
1234
Output:
4321
     
