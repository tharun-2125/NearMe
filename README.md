# Ex04 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
~~~
map.html

<html>

<head>

<title>My City</title>

</head>

<body>

<h1 align="center">

<font color="red"><b>thiruvallur</b></font>

</h1>

<h3 align="center">

<font color="blue"><b>tharun (25014651)</b></font>

</h3>

<center>

I

<img src="map.png" usemap="#MyCity" height="610" width="1450">

<map name="MyCity">

<area shape="rect" coords="100,100,900,900" href="home.html" title="My Home Town">

</map>

</center>

</body>

</html>

home.html

<html>
<head>
<title>My Home Town</title>
</head>

<body bgcolor="cyan">

<h1 align="center">
<font color="red"><b>trl railway station</b></font>
</h1>

<h3 align="center">
<font color="blue"><b>My Home Town -trl railway station</b></font>
</h3>

<hr size="3" color="red">

<p align="justify">
<font face="Georgia" size="5">
thiruvallur railway station is one of the most known places of our sorrounding . it gives life to most of the people. it is also a well known residential area of our sorrounding
</font>
</p>

</body>
</html>

~~~


## OUTPUT

![alt text](<Screenshot (55).png>)


![alt text](<Screenshot (57).png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
