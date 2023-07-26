# visst2023
my summer camp


https://hpssjellis.github.io/visst2023/public/index.html



Send me your URL as an issue!

Links you might find interesting

For the motion assignment you can use your cell phone accelerometer and this static webpage I made here is the main index

https://hpssjellis.github.io/tinyMLjs/public/index.html

here is the best motion page 

https://hpssjellis.github.io/tinyMLjs/public/acceleration/a00-best-acceleration.html



My grade 12 computer programming in javascript page

https://github.com/hpssjellis/high-school-javascript-game-dev-assignment-images

My Robtos course
https://github.com/hpssjellis/maker100

My Huggingface examples

https://hpssjellis.github.io/my-examples-of-huggingfacejs/public/index.html

or use http://huggingface.co/chat

.

.


.

### Arush    https://arushyadavilli.github.io/visst-2023/public/index.html

###  Ansel   https://coconana9010.github.io/VISST-2023-CAMP/public/

###  Max  https://maxbiz100.github.io/SuperAI/public/index.html

###  Koen  https://ppap9264.github.io/visst2023koen/public/index.html

### Lincoln https://thyssenkrupp234.github.io/VISST-2023-lincoln/public/index.html

### Kenji   https://github.com/HonorablePentagon/honorablep

### Andrew https://snare555.github.io/VISST2023/public/






Lincoln's code

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>SimpleJS</title>
        <link rel="stylesheet" href="css/index.css">
    </head>
    <body>
        <input type="text" value="hi" id="myText">
        <div id="myDiv">...</div>
        <input type="button" value="in-out" onclick="{
            let myValue = document.getElementById('myText').value;
            document.getElementById('myDiv').innerHTML = myValue;
        }">
    </body>
</html>
```



So let's update this simplejs.html webpage with all the VIDEO FLAC Abilities (except O and C)

V variables
I input output
D decisions (if statements)
E Events (onclick)
O Objects (structs are named variables)

F Functions (named chuncks of code)
L Loops (repeating code)
A Arrays (numbered variables)
C Classes (all the above as one thing)



Code update called ```betterjs.html```

```
        <input type="text" value="7" id="myText">  <!- For input -->

        <div id="myDiv">...</div>   <!- For output -->

        <input type="button" value="in-out" onclick="{  // event
          let myTemp = ''  // an empty variable
          let myValue = parseInt(document.getElementById('myText').value);  // input to a variable
          for (myLoop =0; myLoop < myValue; myLoop++){   // Loop
              if (myLoop > 4) {   // Decision
                   myTemp += myLoop + '<br>'
              }   
          }
          document.getElementById('myDiv').innerHTML = myTemp;  // Output to a webpage element
        }">


The only thing missing from this code is Objects, Arrays and Classes!

```





