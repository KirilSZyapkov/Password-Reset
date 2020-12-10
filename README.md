# Password-Reset

Yet again you have forgotten your password... Naturally it`s not the first time this has happened. Actually you got so tired of it that you decided to help yourself with a smart solution.  

 

Write a password reset program that performs a series of commands upon a predefined string. First, you will receive a string and afterwards, until the command "Done" is given, you will be receiving strings with commands split by a single space. The commands will be the following: 

TakeOdd 

 Takes only the characters at odd indices and concatenates them together to 
obtain the new raw password and then prints it. 

Cut {index} {length} 

Gets the substring with the given length starting from the given index from the password and removes its first occurrence of it, then prints the password on the console. 

The given index and length will always be valid. 

Substitute {substring} {substitute} 

If the raw password contains the given substring, replaces all of its  
occurrences with the substitute text given and prints the result. 

If it doesn’t, prints "Nothing to replace!"
