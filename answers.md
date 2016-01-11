# Exploration: Using the API
The value of -1 is returned by indexOf if the substring does not occur in the string. 

## Exploration: Understand the new method  
findKeyword("She's my sister", "sister", 0);  
Iteration:1    
psn:9    
before: " "  
after: " "  

findKeyword("Brother Tom is helpful", "brother", 0);
Iteration : 1    
psn: 0  
before: " "  
after: " "  

findKeyword("I can't catch wild cats.", "cat", 0);
Iteration : 1  
psn: 8  
before : " "  
after  : "c"    
Iteration : 2  
psn:19  
before : " "  
after : "s"  
Iteration : 3  
return -1   

findKeyword("I know nothing about snow plows.", "no", 0);
Iteration : 1  
psn: 3  
before: "k"    
after "w"  
Iteration : 2  
psn: 7  
before : " "  
after : "t"  
Iteration : 3  
psn: 22  
before : "s"  
after : "w"  
Iteration : 4 b 
return -1
