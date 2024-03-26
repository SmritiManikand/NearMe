# Ex04 Places Around Me
## Date: 26.03.2024

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
MAIN WEB PAGE

<html>
<head>
<title>Locations near me</title>
</head>
<body>
<h1 align="center">TIRUNELVELI</h1>
<br>
<h2 align="center">SMRITI M(212221040157)</h2>
<br>
<center>
<img src="\static\map.png" usemap="#image-map">
</center>
<map name="image-map">
    <area target="_self" alt="palayamkottai" title="palayamkottai" href="palayamkottai.html" coords="620,389,848,332" shape="rect">
    <area target="_self" alt="reddiarpatti" title="reddiarpatti" href="reddiarpatti.html" coords="773,704,947,608" shape="rect">
    <area target="_self" alt="melapalayam" title="melapalayam" href="melapalayam.html" coords="499,564,636,528" shape="rect">
    <area target="_self" alt="vmchatram" title="vmchatram" href="vmchatram.html" coords="973,517,1113,465" shape="rect">
    <area target="_self" alt="pettai" title="pettai" href="pettai.html" coords="65,351,164,305" shape="rect">
</map>
</body>
</html>

palayamkottai.html

<html>
<head>
<title>Location 1</title>
</head>
<body bgcolor="lightseagreen">
<h2 align="center">TIRUNELVELI</h2>
<h3 align="center">PALAYAMKOTTAI</h3>
<p style="background-color: white;height: 2px;"></p>
<br>
1. Palayamkottai is a neighbourhood in Tirunelveli City, incorporated within the Tirunelveli City Municipal Corporation. 
<br>
2. It is situated on the east bank of the Thamirabarani river, with the exception of its downtown area, which is present on the west bank.
<br>
3. Palayamkottai is a residential and educational centre in the Tirunelveli urban agglomeration. A major hub for Christian missions in southern India, it has private Christian schools and colleges, and it has other colleges affiliated with Manonmaniam Sundaranar University in Tirunelveli.
</body>
</html>

reddiarpatti.html

<html>
<head>
<title>Location 2</title>
</head>
<body bgcolor="yellow">
<h2 align="center">TIRUNELVELI</h2>
<h3 align="center">REDDIARPATTI</h3>
<p style="background-color: white;height: 2px;"></p>
<br>
1. According to Census 2011 information the location code or village code of Muthur Reddiarpatti village is 642915.
<br> 
2.  Muthur Reddiarpatti village is located in Palayamkottai taluka of Tirunelveli district in Tamil Nadu, India. It is situated 16km away from Tirunelveli, which is both district & sub-district headquarter of Muthur Reddiarpatti village.
<br>
3. The total geographical area of village is 9.61 hectares.Tirunelveli is nearest town to muthur reddiarpatti for all major economic activities, which is approximately 5km away.
</body>
</html>

melapalayam.html

<html>
<head>
<title>Location 3</title>
</head>
<body bgcolor="lightgreen">
<h2 align="center">TIRUNELVELI</h2>
<h3 align="center">MELAPALAYAM</h3>
<p style="background-color: white;height: 2px;"></p>
<br>
1. Melapalayam is a neighborhood of Tirunelveli City in Tamil Nadu, India situated on the east bank of the Thamirabarani River. 
<br>
2. The neighborhood's name comes from its location west (Tamil: mela) of Palayamkottai. Eighty percent of the population is Muslim.
<br>
3. Melapalayam is 4.1 kilometres (2.5 mi) west of downtown Tirunelveli and is an administrative zone of the Tirunelveli City Municipal Corporation.
</body>
</html>

vmchatram.html

<html>
<head>
<title>Location 4</title>
</head>
<body bgcolor="pink">
<h2 align="center">TIRUNELVELI</h2>
<h3 align="center">V.M.CHATRAM</h3>
<p style="background-color: white;height: 2px;"></p>
<br>
1. V.M. Chatram means Visayaragava Mudaliar Chatram.It is a fast growing urban area located in Tirunelveli district of Tamil Nadu which was formerly a village panchayat.
<br> 
2. V.M. Chatram was developed as a ward of Tirunelveli Corporation from June 1, 1994. 
<br>
3. About 40 acres of agricultural land gets irrigation facility through these ponds. Earth crops such as khatari, mung bean, sugarcane and other crops such as paddy and banana are cultivated here. 
</body>
</html>

pettai.html

<html>
<head>
<title>Location 5</title>
</head>
<body bgcolor="orange">
<h2 align="center">TIRUNELVELI</h2>
<h3 align="center">PETTAI</h3>
<p style="background-color: white;height: 2px;"></p>
<br>
1. Pettai is an industrial suburban area in Tirunelveli. 
<br> 
2. It is approximately 6 kilometers of downtown Tirunelveli along the Southern Railway line to Tenkasi.
<br>
3. It is being administered by the Tirunelveli City Municipal Corporation.
</body>
</html>
```

## OUTPUT

MAIN WEB PAGE

![alt text](s1.png)

PALAYAMKOTTAI

![alt text](s2.png)

REDDIARPATTI

![alt text](s3.png)

MELAPALAYAM

![alt text](s4.png)

VMCHATRAM

![alt text](s5.png)

PETTAI

![alt text](s6.png)

## RESULT
The program for implementing image maps using HTML is executed successfully.
