
## Check username
1. No special characters except dot, underscore. Can be lowercase or uppercase
2. Begining and ending at alphanumeric char
3. No more than 2 dots (underscores) stand by together
4. Length between 6 - 25 characters
> Regex: ` ^(?=.{6,25}$)([a-zA-Z0-9]+([._]?[a-zA-Z0-9])*)$ ` 

 =>>> `(?=.{6,25}$)` check length
 
 =>>> `[a-zA-Z0-9]+` check the first character
 
 =>>> `([._]?[a-zA-Z0-9])*` check rest of username
