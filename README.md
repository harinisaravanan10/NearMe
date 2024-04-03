# Ex04 Places Around Me
## Date: 03.04.2024

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
```
map.html
<html>
<head>
<title>My city</title>
</head>
<body>
<h1 align="center">
<font color="blue"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="lightpink"><b>Harini S(212223040058)</b></font>
</h3>
<centre>
<h4 align="center">
<img src="vellore googlemap.png" usemap="MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,850,400" href="home.html title="MyHomeTown">
<area shape="circle" coords="570,230,45" herf="temple.html" title="Shri Murugam Temple">
<area shape="circle" coords="640,200,30" herf="college.html" title="VIT">
<area shape="circle" coords="1120,360,25" herf="fort.html" title="Vellore Fort">
<area shape="rect" coords="950,120,1100,140" herf="thetre.html" title="PVR cinemas">

</h4>
</map>
</centre>
</body>
</html>

home.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Vellore - My home town</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Vellore (English: VAY-loor), also natively spelt as Velur,[note 1] is a sprawling city and the administrative headquarters 
of Vellore district in the Indian state of Tamil Nadu. It is located on the banks of the Palar River in the northeastern part of Tamil Nadu 
and is separated into four zones that are further subdivided into 60 wards, covering an area of 87.915 km2 and housing 
a population of 423,425 as reported by the 2001 census.
</font>
</p>
</body>
</html>

thetre.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="blue"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>PVR cinemas - Entertainment Centre</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Movie theater in Vellore, Tamil Nadu
Address: silk mill, 33/5,14th east cross road, Katpadi Main Rd, near Damro showroom, Gandhi Nagar, Vellore, Tamil Nadu 632006
</font>
</p>
</body>
</html>

fort.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lightblue">
<h1 align="center">
<font color="blue"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Vellore Fort - Tourist Spot</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Vellore Fort is a large 16th-century fort situated in heart of the Vellore city, 
in the state of Tamil Nadu, India built by the Emperors of Vijayanagara. 
The fort was at one time the imperial capital of the Aravidu Dynasty of the Vijayanagara Empire.
</font>
</p>
</body>
</html>

college.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="grey">
<h1 align="center">
<font color="black"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="black"><b>VIT - Educational University</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Vellore Institute of Technology is a private deemed university located 
in Katpadi in Vellore, Tamil Nadu, India. The institution offers 66 Undergraduate, 
58 Postgraduate, 15 Integrated, 2 Research and 2 M.Tech Industrial Programmes
</font>
</p>
</body>
</html>

temple.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="lightgreen">
<h1 align="center">
<font color="blue"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Shri Murugan Temple - Devotional Centre</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Vellore Arulmigu Ratnagiri murugan temple is a temple dedicated to the god Murugan, 
in Thirumanikundram, Vellore, India. It was constructed around the 14th century, 
and was mentioned by the 14th century poet Arunagirinathar.
</font>
</p>
</body>
</html>

```

## OUTPUT
![vellore googlemap](https://github.com/harinisaravanan10/NearMe/assets/149035598/187ab163-73cb-4320-8d05-049f48e57431)

![home](https://github.com/harinisaravanan10/NearMe/assets/149035598/97e1cb68-08c5-4b2c-998b-81c9870d483a)

![thetre](https://github.com/harinisaravanan10/NearMe/assets/149035598/68c101de-8e29-4823-a50d-862c3a948925)

![fort](https://github.com/harinisaravanan10/NearMe/assets/149035598/914e6764-b8d8-430d-a8b5-94860a44202a)

![temple](https://github.com/harinisaravanan10/NearMe/assets/149035598/0593df8a-20ee-4fcb-95e9-e1963b6d1ef6)

![college](https://github.com/harinisaravanan10/NearMe/assets/149035598/7f34c4e0-25ee-4cea-ab09-fb824a468aa1)


## RESULT
The program for implementing image maps using HTML is executed successfully.
