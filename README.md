# Data-Structure-Algorithms
An overview of data structures and algorithms.

# String
## Constructor
String() <br> 
String(String value) <br> 
String(char[] array) <br> 
String(char[] array, int offset, int length) <br> 
String(StringBuilder builder) <br> 

## StringBuilder
sb.append('c'); <br> 
sb.deleteCharAt(sb.length() - 1); <br> 
sb.toString(); <br> 
## Operation

### split()
String[] array = str.split("\\s+"); // by spaces <br> 
String[] astr = str.split("[, ?.@]+"); <br> 

### Convert
#### string to int
String number = "10"; <br> 
int result = Integer.parseInt(number); <br> 

Integer result = Integer.valueOf(number);	 <br> 
#### int to string
Integer.toString(number); <br> 

StringBuilder sb = new StringBuilder(); <br> 
sb.append(number); <br> 
String numberAsString = sb.toString(); <br> 



