# Leap-Year-progra-min-Python

def is_leap(year):
    leap = False
    
    # Write your logic here
    #if((Year % 400 == 0) or  (Year % 100 != 0) and  (Year % 4 == 0)):  
    if ((year%400 == 0) or (year%100 != 0) and (year %4 == 0)):
        leap = True
    else:
        leap = False
    return leap

year = int(input())
print(is_leap(year))









good and optimized one 
