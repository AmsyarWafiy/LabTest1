def countSetBits( n): 
      
    # base case 
    if (n == 0): 
        return 0
  
    else: 
  
        # if last bit set add 1 else 
        # add 0 
        return (n & 1) + countSetBits(n >> 1) 
          
# Get value from user 
n = 9
  
# Function calling 
print( countSetBits(n))      
