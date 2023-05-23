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
  
  To create a variable in JavaScript we use the **var** keyword succeeded by the variable name then 'is equals to' sign (which is called declaration), then variable's values in double quotatoin marks and then semicolon.
  
