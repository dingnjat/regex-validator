
## Check username
> Regex: ` ^(?=.{6,25}$)([a-zA-Z0-9]+([._]?[a-zA-Z0-9])*)$ ` 

1. No special characters except dot, underscore. Can be lowercase or uppercase
2. Begining and ending at alphanumeric char
3. No more than 2 dots (underscores) stand by together
4. Length between 6 - 25 characters

 =>>> `(?=.{6,25}$)` check length
 
 =>>> `[a-zA-Z0-9]+` check the first character
 
 =>>> `([._]?[a-zA-Z0-9])*` check rest of username
## check full name
> Regex: `^(?=.{2,40}$)([^' \-._!¡?÷?¿\/\\+=@#$%ˆ&*(){}|~<>;:[\]]+([. '-]?[^' \-._!¡?÷?¿\/\\+=@#$%ˆ&*(){}|~<>;:[\]])*)$`
1. Accept dot, space, single quote, hyphen. No more than 1 character of above set stands sequencely. Non of them stands start or end position
2. Length between 2 - 40 characters (Han character name maybe has 2 character)

