# visst2023
my summer camp


https://hpssjellis.github.io/visst2023/public/index.html



Send me your URL as an issue!

Links you might find interesting

For the motion assignment you can use your cell phone accelerometer and this static webpage I made here is the main index

# My Profile Github Page

https://github.com/hpssjellis

# tinyMLjs

https://hpssjellis.github.io/tinyMLjs/public/acceleration/a00-best-acceleration.html



# Javascript programming course Grade 11-12

https://github.com/hpssjellis/high-school-javascript-game-dev-assignment-images

# Robotics Course Grade 11-12  

https://github.com/hpssjellis/maker100


# Huggingface examples

https://hpssjellis.github.io/my-examples-of-huggingfacejs/public/index.html

or use http://huggingface.co/chat


# TensorflowJS stuff I made years ago

https://hpssjellis.github.io/beginner-tensorflowjs-examples-in-javascript/#tfjs-models
.

.


## Students who have sent their URL as an issue

### Arush    https://arushyadavilli.github.io/visst-2023/public/index.html

###  Ansel   https://coconana9010.github.io/VISST-2023-CAMP/public/

###  Max  https://maxbiz100.github.io/SuperAI/public/index.html

###  Koen  https://ppap9264.github.io/visst2023koen/public/index.html

### Lincoln https://thyssenkrupp234.github.io/VISST-2023-lincoln/public/index.html

### Kenji   https://honorablepentagon.github.io/honorablep/public/index.html

### Andrew https://snare555.github.io/VISST2023/public/






### Lincoln's code

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



# Thursday coding

So let's update this simplejs.html webpage with more of the VIDEO FLAC coding abilities

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
<script>
function myMain(){   // a funtion definition
   let myTemp = ''  // an empty variable
   let myValue = parseInt(document.getElementById('myText').value);  // input to a variable
   for (myLoop =0; myLoop < myValue; myLoop++){   // Loop
      if (myLoop > 4) {   // Decision
         myTemp += myLoop + '<br>'
      }   
   }
   document.getElementById('myDiv').innerHTML = myTemp;  // Output to a webpage element         
}
</script>


<input type="text" value="7" id="myText"> 

<div id="myDiv">...</div>  

<input type="button" value="in-out" onclick="{  // event definition
    myMain()  // function activation
}"><br>


The only thing missing from this code is Objects, Arrays and Classes!

```


## Thursday / Friday camp vision deployment to WASM on a webpage. 

Basically click edgeimpules deployment, choose WASM, download it, unzip it and drag the entire unzipped folder into your public folder on Github.
On your index page make a link to the folder

Main Tutorial Link   https://hpssjellis.github.io/multi-language-edgeimpulse-tutorial-vision-cell-phone/

The tutorial is for the Vision Classification example but I think it also works with the FOMO example.

The download index.html file to replace the edgeimpulse unzipped folder index.html file for vision - classification  [here](https://github.com/hpssjellis/multi-language-edgeimpulse-tutorial-vision-cell-phone/tree/main/download)


Try this one for FOMO  [download-fomo](download-fomo)

Good luck. Start thinking about your Project for Friday.



## Friday: Project or Regression. 
Basically with Linear Regression the labels are numbers and reflect the size of a sample. Easiest with vision classification.




Huggingface chat that we can control

https://huggingface.co/spaces/huggingfacejs/streaming-text-generation

I will try to simplify it here

https://hpssjellis.github.io/my-examples-of-huggingfacejs/public/chat/hugchat00.html








