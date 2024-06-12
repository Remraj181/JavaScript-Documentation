# JavaScript   Notes
![alt text](29.jpg)

                                                                 Prem kumar
                                                                 31/05/2024


# Table of contents

1.  What Is javascript
2. Setting Up VsCode
3. Our 1st JS Code
4. Variables In Js
5. Variable Rules
6.  let, const & var
7.  Data Types in Js
8.  Comments in JS
9.  Operators in JS
10. Loops
11. Strings in JS 
12. String Methods in JS
13. ARRAYS
14. Functions
15. Dom
16. Events

# 1.  What Is javascript
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

    
                $ sudo apt-get update
- Step 6. After update system Now you can Install VS Code using the following command:

  
           $ sudo apt install vscode .

- Step 6. Open VS Code.          





   ![alt text](1.jpg)

- Step 6:- Create a new file.
![alt text](30.jpg)
<br>

# 3.  Our 1st JS Code


 > `Console.log is used to log (print) a message to the console.`
- Frist progarm in VS Code type in                                           
- Console.log(“Hello”);
- Console.log(‘Hello’);
- ➡️  Go to Google and inspect the console and run the program.

![alt text](2.jpg)

-  ➡️  Go to Google and inspect the console and run the program.

-   ➡️    VS code program run.
  
 ![alt text](3.jpg) 

-  To run JavaScript programs on the browser.
-  You will have to create a HTML file.




 ## ➡️    HTML :-
        HTML   ➡  Hypertext Markup Language

- ➡️ Diagram connected to JavaScript browser.
  


                  HTML <--> BROWSER  <--> JavaScript
                       <-----------------> 
                       
![alt text](4.jpg)                                  

##  HTML to JavaScript connected.
     </ Body>
       <script src=”index.js”></script>

### HTML Code:-
![alt text](5.jpg) 

### JS Code:-
![alt text](6.jpg) 
### Output:-
![alt text](7.jpg) 
# 4. Variables In Js
- Variables are containers for data.
# 5.Variable Rules
- Variable names are case sensitive; “a” & “A” is different.
- Only letters, digits, underscore( _ ) and $ is allowed. (not even space)
- Only a letter, underscore( _ )or $ should be 1st character.
- Reserved words cannot be variable names.
# 6. let, const & var
- **var** :- Variable can be re-declared & updated. A global scope variable.
- **let** :- Variable cannot be re-declared but can be updated. A block scope variable.
- **const** : Variable cannot be re-declared or updated. A block scope variable.
# 7.Data Types in JS 
- **Primitive Types** : Number, String, Boolean, Undefined, Null, BigInt, Symbol
  
# 8. Comments in JS
` //This is a single line comment`
<br>
`/* This is a multi-line comment.*/`

<br>

![alt text](8.jpg)


# 9.Operators in JS
- Used to perform some operation on data.
  
       Arithmetic Operators
          +, -, *, /
-  Modulus (+)
-  Exponentiation (-)
-  Increment (*)
-  Decrement (/)
  ## program:-
  ![alt text](10.jpg)
  ## output:-
  ![alt text](9.jpg)

  # LOOP IN JS
 
  # 10. Loop
  - Loops are used to execute a piece of code again & again.

  1. for Loop 
  2. while Loops
  3. do-while loop
  4. for-of Loop
  5. for-in   

## for Loop
            for (let i = 1; i <= 5; i++) {
            console.log("apna college");
            } 
## Program              
 ![alt text](12.jpg)
 ## output
 ![alt text](11.jpg)

 ## Infinite Loop:- 
-  A Loop that never ends.
  
  ## while Loop:-
                while (condition) {
                // do some work
                     }
## Program              
![alt text](13.jpg)
 ## output
![alt text](14.jpg)                  

## do-while Loop
         do{
          //do some work
         }while(condition);
## Program              
![alt text](15.jpg)
 ## output
![alt text](16.jpg)            
## for-of Loop
           for (let key in objVar) {
           //do some work
             }
## Program              
![alt text](17.jpg)
 ## output
![alt text](18.jpg) 
## for-in Loop
              for (let key in objVar) {
                //do some work
                 }         
## Program              
![alt text](19.jpg)
 ## output
![alt text](20.jpg) 
#  11. Strings in JS 
- String is a sequence of characters used to repreesent text.            
### Create String
         let str = "Hello";
### String Length  
                  str.length
### String Indices
              str[0], str[1], str[2] 

## Program              
![alt text](21.jpg)
 ## output
![alt text](22.jpg)   
 #  12. String Methods in JS   
 - These are built-in functions to manipulate a string.  
 - str.toUpperCase( )
- str.toLowerCase( ) 
- str.trim( )    // removes whitespaces 
- str.slice(start, end?) // returns part of string
- str1.concat( str2 ) //joins str2 with str1
- str.replace( searchVal,newval)
- str.charAt( idx ) 
## Program              
![alt text](23.jpg)
 ## output
![alt text](24.jpg)  
#  13. Array  
- Collections of items.
### Create Array
- let heroes = [ “ironman”, “hulk”, “thor”, “batman” ];
- let marks = [ 96, 75, 48, 83, 66 ];
- let info = [ “rahul”, 86, “Delhi” ];
### Array Indices
- arr[0], arr[1], arr[2] ....
## Program              
![alt text](25.jpg)
 ## output
![alt text](26.jpg) 
### Array Methods
                  Push( ) : add to end
                  Pop( ) : delete from end & return
                  toString( ) : converts array to string
                  Concat( ) : joins multiple arrays & returns result
                  Unshift( ) : add to start
                  shift( ) : delete from start & return
                  Slice( ) : returns a piece of the array
                  Splice( ) : change original array(add,remove,replace)

# 14. Functions 
- Block of code that performs a specific task, can be invoked whenever needed               
### Function Definition
                     function functionName( ) {
                      //do some work
                     }

### Function Call
                  functionName( );

-  Compact way of writing a function.

                       const sum =(a,b)=>{
                        return a+b;
                       }
### forEach Loop in Arrays
-  arr.forEach( callBackFunction )    
-  CallbackFunction : Here, it is a function to execute for each element in the array.
- *A callback is a function passed as an argument to another function.

                            arr.forEach( ( val ) => {
                             console.log(val);
                              })                        


###  Map   
- Creates a new array with the results of some operation. The value its callback returns are
used to form new array.
- arr.map( callbackFnx( value, index, array))
               
                                   let newArr = arr.map( ( val ) => {
                                  return val * 2;
                                   })
                                
###  Filter 
- Creates a new array of elements that give true for a condition/filter.
Eg: all even elements.

                             let newArr = arr.filter( ( ( val )) => {
                              return val % 2 === 0;
                               })  





###  Reduce  
- Performs some operations & reduces the array to a single value. It returns
that single value.

# 15. DOM
## What is DOM?
- When a web page is loaded, the browser creates a Document Object Model (DOM)of the page.
![alt text](27.jpg) 
## Selecting with id
- document.getElementById(“myld")
## Selecting with class
- document.getElementsByClass Name("myclass)
## Selecting with tag
- document.getElementsByTagName(“p”)
## Properties
-  tagName : returns tag for element nodes
- innerText : returns the text content of the element and all its children
- innerHTML : returns the plain text or HTML contents in the element  
- textContent : returns textual content even for hidden elements.  
# 16. Event
- The change in the state of an object is known as an Event.
- Events are fired to notify code of "interesting changes" that may affect code execution.
- Mouse events (click, double click etc.)
- Keyboard events (keypress, keyup, keydown)
- Form events (submit etc.)
- Print event & many more

                           node.event = ( ) => {
                           //handle here
                            }
                            example
                                btn.onclick = ( ) => {
                             console.log(“btn was clicked”);
                                  }

# Conclusion  
- JavaScript has solidified its position as a fundamental technology in modern web development. Its ability to create dynamic and interactive user experiences has transformed the web from static pages to vibrant, responsive applications. The language's versatility, from client-side scripting to server-side applications using Node.js, underscores its importance in the tech ecosystem.

- In conclusion, mastering JavaScript is essential for anyone looking to excel in web development. Its widespread adoption and continuous improvements make it a crucial skill for developers aiming to create modern, interactive, and efficient web applications.
# Reference Link                                
## [JavaScript Link:-](https://www.youtube.com/watch?v=VlPiVmYuoqw&t=29691s)

# Thank You!
