# Ex.04 Images as Hyperlinks
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
~~~
<html>
<body>
<h1>Plougher</h1>
<a href="https://www.google.com/search?q=plougher&source=lmns&bih=625&biw=1366&hl=en&sa=X&ved=2ahUKEwj6r4bw4Mz-AhXCBrcAHQGvDsQQ_AUoAHoECAEQAA">
<img src="plougher.jpg"
width="200" height="200"></a>
<br>
<br>
<h1>Seeder</h1>
<a href="https://www.google.com/search?q=seeder&oq=seeder&aqs=chrome.0.69i59j0i10i131i433i512l2j0i512j0i20i263i512j0i512l2j5.1301j0j7&sourceid=chrome&ie=UTF-8">
<img src="seeder.jpg"
width="200" height="200"></a>
<br>
<br>
<h1>Tillage</h1>
<a href="https://www.google.com/search?q=tillage&source=lmns&bih=568&biw=1366&hl=en&sa=X&ved=2ahUKEwjE_dXH5cz-AhX71XMBHVq6CPQQ_AUoAHoECAEQAA">
<img src="tillage.jpg"
width="200" height="200"></a>
<br>
<br>
<h1>Sickle</h1>
<a href="https://www.google.com/search?q=sickle&source=lmns&bih=631&biw=1498&hl=en&sa=X&ved=2ahUKEwjZrYCv58z-AhXPk9gFHSQqAcIQ_AUoAHoECAEQAA">
<img src="sickle.jpg"
width="200" height="200"></a>
<br>
<br>
<h1>Spading fork</h1>
<a href="https://www.google.com/search?q=spading+fork&oq=spading+fork&aqs=chrome.0.69i59j0i67i650l3j0i512l6.3043j1j7&sourceid=chrome&ie=UTF-8">
<img src="spading fork.jpg"
width="200" height="200"></a>
<body>
</html>
~~~


## OUTPUT
![hyperlink 1](https://user-images.githubusercontent.com/127816323/235446694-99afd156-7254-4fbb-99b7-1366d4b68bc3.png)
![hyperlink 2](https://user-images.githubusercontent.com/127816323/235446757-776402ec-278f-40c9-95fd-b87290192e29.png)
![hyperlink 3](https://user-images.githubusercontent.com/127816323/235446803-8c55935c-75e6-4ddf-842e-aa03009b41f0.png)




## RESULT
 Images as hyperlinks is implemented successfully.
