#  store person name 
fname = input ("enter your first name ")
lname = input ("enter your second name ")

# store inputs
sub1  = input ("enter your  salary ")
sub2  = input ("enter your tax ")
sub3  = input ("enter your expensence ")

total = float(sub1)-float(sub2) -float(sub3) 

print("your name is {0} {1}".format(fname , lname))
print("__________________________________________________")
print ("your salary is {0}\nyour tax is {1}\nyour total expencence is {2}\n your total savings is  {3}".format(sub1,sub2,sub3,total))
print("******note this information wiil nat be saved******")
