
![29](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/147d20f3-6af5-4edd-b238-357fdf95dd5b)

                                                                 Prem kumar
                                                                 31/05/2024


# Table of contents

1. What Is javascript
2. Setting Up VsCode
3. Our 1st JS Code
4. Variables In Js
5. Variable Rules
6.  let & const 
7.  Data Types in Js
8.  Comments in JS
9.  Operators in JS
10. Loops
11. Strings in JS 
12. ARRAYS
13. Functions

#  1. What Is javascript
>JS is a programming language. We use it to give instructions to the computer.

              Input (code)  ➡ Computer  ➡ Output

<br>


# 2.  Setting Up VsCode
- Step 1:- Search on Google or Chrome Download VsCode.
- Step 2:- click on the first link.
  
  - VsCode Download :-
  ![vs](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/98d9c8d4-e78f-4256-9e9d-2e471527787d)



- Step 3:- After completion VS Code, Check your download Folder.
- Step 4:- Open Terminal in Linux or  for shortcut click (ctrl + alt + t)
- Step 5:- Check if the system up-to-date using following command :

    
                $ sudo apt update
- Step 6. After update system Now you can Install VS Code using the following command:

  
           $ sudo apt install vscode .

- Step 6. Open VS Code.          


![1](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/50dff81d-7031-4764-ae73-cf8b09530332)

- Step 6:- Create a new file.

 
![30](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/578c03b6-b793-4d49-bf6d-34903a062d87)
<br>

# 3.  Our 1st JS Code


 > `Console.log is used to log (print) a message to the console.`
- Frist progarm in VS Code type in                                           
- Console.log(“Hello”);
- Console.log(‘Hello’);
- ➡️  Go to Google and inspect the console and run the program.

![2](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/d45fc2e8-9565-46a1-82e6-607c2b82d0b8)

-  ➡️  Go to Google and inspect the console and run the program.

-   ➡️    VS code program run.
  
 ![3](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/1a7bab0c-dda9-42c2-923f-8fa879f2339c) 

-  To run JavaScript programs on the browser.
-  You will have to create a HTML file.




 ## ➡️    HTML :-
        HTML   ➡  Hypertext Markup Language

- ➡️ Diagram connected to JavaScript browser.
  


                  HTML <--> BROWSER  <--> JavaScript
                       <-----------------> 
                       
![4](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/69184b25-b447-44ab-9e97-ba338511bf34)                                 

##  HTML to JavaScript connected.
     </ Body>
       <script src=”index.js”></script>

### HTML Code:-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script src="index.js"></script>
</body>
</html>

### JS Code:-
![6](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/fcfec36d-45ab-480f-ba47-11c06d1ba61e)
### Output:-
![7](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/566386d8-10ae-4d0c-8f2f-86e9cda2d2fc)
# 4. Variables In Js
- Variables are containers for data.
# 5.Variable Rules
- Variable names are case sensitive; “a” & “A” is different.
- Only letters, digits, underscore( _ ) and $ is allowed. (not even space)
- Only a letter, underscore( _ )or $ should be 1st character.
# 6. let & const 
- **let** :- Variable cannot be re-declared but can be updated. 
- **const** : Variable cannot be re-declared or updated.
# 7.Data Types in JS 
- **Primitive Types** : Number, String, Boolean
  
# 8. Comments in JS
` //This is a single line comment`
<br>
`/* This is a multi-line comment.*/`

<br>

![8](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/a74490eb-2660-4a0a-924b-0fd9641e383d)


# 9.Operators in JS
- Used to perform some operation on data.
  
       Arithmetic Operators
          +, -, *, /
-  Modulus (+)
-  Exponentiation (-)
-  Increment (*)
-  Decrement (/)
  ## program:-
![10](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/803639ac-41dc-4bb6-96a1-9de13ebf0044)
  ## output:-
 ![9](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/34f0c66a-a96c-472f-8bb7-2d8242756492)

  # LOOP IN JS
 
  # 10. Loop
  - Loops are used to execute a piece of code again & again.

  1. for Loop 
  2. while Loops
  3. do-while loop  

## for Loop
            for (let i = 1; i <= 5; i++) {
            console.log("apna college");
            } 
## Program              
 ![12](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/97c697ed-d168-4663-8d10-ba5bc90f4d42)
 ## output
![11](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/6a8f88ae-a996-459a-a58b-8595ae0e3869)
  
  ## while Loop:-
                while (condition) {
                // do some work
                     }
## Program              
![13](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/cf7a5c68-1f88-42ad-a45f-557154fc17c8)
 ## output
![14](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/f0e1b6d5-a8e8-40ad-9ec0-f69140192bfe)                 

## do-while Loop
         do{
          //do some work
         }while(condition);
## Program              
![15](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/f2a813e9-dbdd-4a61-916d-11d2f5372fcd)
 ## output
![16](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/6670e121-4910-4e43-b9fa-5f793eab2ecc)          

            
#  11. Strings in JS 
- String is a sequence of characters used to repreesent text.            
### Create String
         let str = "Hello";
### String Length  
                  str.length
### String Indices
              str[0], str[1], str[2] 

## Program              
![21](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/59cf1cb5-635c-4b46-9249-727c89173f95)
 ## output
![22](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/6f936345-68f1-41e3-98d7-9b5b90cb69dd)  
 #  12. String Methods in JS   
 - These are built-in functions to manipulate a string.  
 - str.toUpperCase( )
- str.toLowerCase( ) 
 
## Program              
![23](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/fbf43c66-cd78-4e02-b264-d7b76cadffa3)
 ## output
![24](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/c2edbfd4-5832-45e4-8987-bc007bd8125b)  
#  13. Array  
- Collections of items.
### Create Array
- let heroes = [ “ironman”, “hulk”, “thor”, “batman” ];
- let marks = [ 96, 75, 48, 83, 66 ];
- let info = [ “rahul”, 86, “Delhi” ];
### Array Indices
- arr[0], arr[1], arr[2] ....
## Program              
![25](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/a14860a8-5129-409d-9dd8-df0ffd4895fd)
 ## output
![26](https://github.com/Remraj181/JavaScript-Documentation/assets/162377025/31a2d933-d9fa-47fb-87eb-25d4ef138bb4)
### Array Methods
                  Push( ) : add to end
                  Pop( ) : delete from end & return
                 
# 14. Functions 
- Block of code that performs a specific task, can be invoked whenever needed               
### Function Definition
                     function functionName( ) {
                      //do some work
                     }

# Conclusion  
- JavaScript has solidified its position as a fundamental technology in modern web development. Its ability to create dynamic and interactive user experiences has transformed the web from static pages to vibrant, responsive applications. The language's versatility, from client-side scripting to server-side applications using Node.js, underscores its importance in the tech ecosystem.

- In conclusion, mastering JavaScript is essential for anyone looking to excel in web development. Its widespread adoption and continuous improvements make it a crucial skill for developers aiming to create modern, interactive, and efficient web applications.
# Reference Link                                
## [JavaScript Link:-](https://www.youtube.com/watch?v=VlPiVmYuoqw&t=29691s)

# Thank You!
