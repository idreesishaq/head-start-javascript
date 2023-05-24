# head-start-javaScript

1. JavaScript is one of the most advanced and powerful programming language.
2. JavaScript is a __High-Level__ and __Interpreter__ language.
3. Since It is interpreter language, it execute code line by line. Therefore, in case of any error to execute of any line of code, it won't go further to execute the rest of the code, unless or until error is not resolved.
4. Do not confuse with the name __JavaScript.__ It doesn't have anything of __Java__ which is a seperate programming language.
5. You do not need to download or install any software to work in JavaScript.
6. JavaScript runs in browser. so every brower do have JavaScript engine.
7. To write JS code open your favorite code editor like (Visual Studio Code, atom, sublime, etc) or simply you can write JS code in notepad or notepad++, then save the code file with the extension of __.js__.
8. To link the external JS file to the html, write the <script> tag with the filename and location under the __src__ attribute like this.
```
<srcipt src=main.js> </script>
```
  usually written at just before the closing tag of html body.

9. JavaScript can written as __external__ as well as __internal__.
10. An another way of writing javascript on realtime is to write the JavaScript code on the on the **console**.<br>
  i). open favorite browser (mine chrome).<br>
  ii) Press F12 key, or right click then click the inspect button. A side window on the browser window will be open.<br>
  iii) Now click the **console** button on upper right, adjacent with the **Element** button. <br>
  iv) Here you can write Javascript code. <br>

# JavaScript Keywords
  --Keywords-- or --reserved words-- are words that have a special meaning to JavaScript and act as **programming instruction**
  
  | abstract | delete | goto | new | this |
  | --- | --- | --- | --- | --- |
  | **as** | **do** | **if** | **null** | **throw** |
  | **boolean** | **double** | **implements** | **package** | **throws** |
  | **break** | **else** | **import** | **private** | **transient** |
  | **byte** | **enum** | **in** | **protected** | **true** |
  | **case**| **export** | **instanceof** | **public** | **try** |
  | **catch** | **extends** | **int** | **return** | **typeof** |
  | **char** | **false** | **interface** | **short** | **use** |
  | **class** | **final** | **is** | **static** | **var** |
  | **continue** | **finally** | **long** | **super** | **void** |
  | **const** | **float** | **namespace** | **switch** | **volatile** |
  | **debugger** | **for** | **native** | **synchronized** | **while** |
  | **default** | **function** |  |  | **with** |
  
<hr>
  
  ## Alert
  
  ```
  alert("Hello World!")
  ```
  alert is a keyword that displays a message in a box on the browser window.
  
  ## Variables
  A variable is a container that stores some information in terms of data. The value of the data can change, depanding on the conditions or instructions that we have passed to the program. The information of data stored in a variable can be a string, number, alpha numberic values or any characters.
  
  To create a variable in JavaScript we use the **var** keyword preceded by the variable name then 'is equals to' sign (which is called declaration), then variable's values in double quotatoin marks and then semicolon. 
  ```
  var name = "idrees";
  ```
  We can also store any number value in a variable like this.
  ```
  var age = 27;
  ```
  Yes you have spotted right that here a number without quotation marks (""), whereas a string (any number characters) is in quotation mark.<br>
  but what happen if we write number is quotation mark. e.g;
  
  ```
  var age = "27";
  ```
  Well we can write, and we do in some cases, where we have to display numbers as string
  ```
  var myAddress = "Street 42 Block 5 Down town Karachi 75300";
  ```
  They that type of datatype cannot do mathematical operations. So if we want arithmatic operations with number we creat variable as number. e.g
  ```
  var num1 = 5;
  var num2 = 13;
  var total = num1 + num2;
  ```
  Here the variable **total** will store the numeric value **18**. Whereas in the following example the variable will hold the string value **"513"**. Because it simply concatenates the string values rather than adding them.
  ```
  var num1 = "5";
  var num2 = "13";
  var totol = num1 + num2;
  ```
  ### Variable Naming Rules
  There are some consideration we should keep in mind while we are creating a variable and naming it. 
  - We cannot enclose a variable names in quotation marks. e.g. `var "myName" = "idrees";`
  - A variable cannot ba a number or start with a number e.g. `var 1num = 15;`
  - It cannot be any of JavaScript's reserved words or keywords e.g. `var final = "The last chance";`
  - A variable cannot contain any spaces. e.g `var my name = "idrees";`
  - A variable name can contain only letter, numbers, dollar signs and underscores. e.g `myName, Name1, my_name, myName$, and etc.`
  - Although a variable name cannot be any of JavaScript's keywords but I contain keywords. e.g `userAlert, myVar, var1, etc.`
  - Capital letter are fine but be careful **name** is not equal to **Name**. JavaScript is a case sensitive language. If you store a value "Gyrfalcon"in a variable named **bird**, and then ask JavaScript for the value assigned to **Bird**, you'll come up empty.
  - It a preferred style convention to use **camelCase** in naming a variable in JavaScript, among JavaScript programming. 
  Here is a list of style convention.
  + **snake case** `my_first_name`
  + **kebab case** `my-first-name`
  + **camel case** `myFirstName`
  + **pascal case** `MyFirstName`

