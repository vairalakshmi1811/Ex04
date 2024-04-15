# Ex.04 Images as Hyperlinks
## DATE:15/04/2024
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
    <head>
        <title>AGRICULTURE</title>
    </head>
    <body bgcolor="lightgreen">
        <h1 align="center"><u>AGRICULTURE</u></h1>
        <h2>Paddy</h2>
        <a href="https://www.britannica.com/topic/paddy">
         <img src="d:\official\paddy.jpeg" height="200" width="200" border="2"/>
        </a><br><br>
        <h2>Maize</h2>
        <a href="https://iimr.icar.gov.in/?page_id=1785" >
        <img src="d:\official\maize.jpeg" height="200" width="200" border="2"/>
        </a><br><br>
        <h2>Tractor</h2>
        <a href="https://en.wikipedia.org/wiki/Tractor">
        <img src="d:\official\tractor.jpeg" height="200" width="200" border="2"/>
        </a><br><br>
        <h2>Rotavatar</h2>
        <a href="https://www.swanagro.in/en/product/rotary-tiller/1">
        <img src="d:\official\rot-mech.jpg" height="200" width="200" border="2"/>
        </a><br><br>
        <h2>Fertilizer</h2>
        <a href="https://www.swanagro.in/en/product/rotary-tiller/1">
        <img src="d:\official\ferti.jpeg" height="200" width="200" border="2"/>
        </a>
        
    </body>
</html>
```

## OUTPUT
<img width="959" alt="img-output1" src="https://github.com/vairalakshmi1811/Ex04/assets/165985148/999669ca-2b0b-40a3-9d1a-d69e7c88d6e5">
<img width="959" alt="img-output2" src="https://github.com/vairalakshmi1811/Ex04/assets/165985148/3dfedb66-3429-4f96-b9ee-b80d3646471f">
<img width="959" alt="img-output3" src="https://github.com/vairalakshmi1811/Ex04/assets/165985148/bee5ae01-d27f-4c02-991c-1bb95f70b171">





## RESULT
 Images as hyperlinks is implemented successfully.
