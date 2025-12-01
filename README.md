# Ex03 Places Around Me
## Date:1/12/2025 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
map.html

<html>
    <head>
        <title>Chennai</title>
    </head bgcolor="redclear">
    <body>
        <h1>Chennai-Vadachennai</h1>
        <br>
        <br>
        <h2>Aswath Ragavan MG (25013229)</h2>
        <img src="Vadachennai111.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Tiruvottiyur Railway Station" title="Tiruvottiyur Railway Station" href="railway.html" coords="654,368,850,453" shape="rect">
    <area target="" alt="Kaladipet Market" title="Kaladipet Market" href="kaladipet.html" coords="878,643,133" shape="circle">
    <area target="" alt="Tiruvottiyur Beach(N4)" title="Tiruvottiyur Beach(N4)" href="beach.html" coords="1336,113,1094,780" shape="rect">
    <area target="" alt="Tiruvottiyur Market" title="Tiruvottiyur Market" href="market.html" coords="939,106,1041,242,891,281,1044,242,856,316" shape="poly">
    <area target="" alt="Petrol Plant Manali" title="Petrol Plant Manali" href="plant.html" coords="195,566,191" shape="circle">
</map>
    </body>
</html>


plant.html

<html>
    <head>
        <title>Chennai</title>
    </head>
    <body align="center" bgcolor="yellow"></body>
    <h1>Chennai-Vadachennai</h1>
    <h1>Manali Petroleum Plant</h1> 
    <br>
    <br>
    <hr> 
    <h1>This Place is located in North part of Chennai
        The term "Manali petrol plant" likely refers to one of two major industrial facilities in Manali, Chennai: the CPCL Manali Refinery or the Manali Petrochemicals Limitedplant
        MMTPA capacity that produces fuels like LPG, Motor Spirit, and High Speed Diesel.
    </h1>    
</html>

market.html

<html>
    <head>
        <title> Market</title>
    </head>
    <body align="center" bgcolor="orange"</body>
    <h1>Chennai-Vadachennai</h1>
    <h1>Tiruvottiyur Market</h1>
    <br>
    <br>
    <hr>
    <h1>This is the one of the famous market around north chennai
        the Tiruvottiyur market is a local market in chennai known for its fresh vegetables especially
        in the morning market sale it contains around 200+shops it has major fishing hub</h1>  
</html>

beach.html

<html>
    <head>
        <title>Beach</title>
    </head>
    <body align= "center" bgcolor="skyblue"</body>
    <h1> Chennai-Vadachennai</h1>
    <h1>N4 Beach</h1>    
    <br>
    <br>
    <hr>
    <h1>N4 Beach is a lesser-known, quiet beach in Chennai, India, located next to the busy Kasimedu Fishing Harbour. It is a popular spot for locals who enjoy its peaceful atmosphere, and it's known for its unique view of fishing boats and the activity around the harbor, especially during sunrise and sunset.</h1>
</html>

kaladipet.html

<html>
    <head>
        <title>kaladipet</title>
    </head>
    <body align="center" bgcolor="green"</body>
    <h1>Chennai-Vadachennai</h1>
    <h1>kaladipet Market</h1>
    <br>
    <br>
    <hr>  
    <h1>Kaladipet is a bustling market area in Thiruvottiyur, North Chennai, known for its local markets, including vegetable and fish markets, and historical significance. It's a mixed-use residential and commercial locality with good transportation, including a nearby metro station, though it can experience heavy traffic jams and parking issues</h1>
    
</html>

railway.html

<html>
    <head>
        <title>railway</title>
    </head>
    <body align="center" bgcolor="gold"</body>
    <h1>Chennai-Vadachennai</h1>  
    <h1>Tiruvottiyur Railway Station</h1>
    <br>
    <br>
    <hr>
    <h1>Tiruvottiyur (TVT) is a suburban railway station on the Chennai Suburban Railway's north line, located about 9 km north of Chennai Central. It is a busy station with three platforms, serving as a major hub for commuters. The station is part of the Chennai Suburban Railway Network and is also near the Chennai Metro's Blue Line extension, providing alternative transportation options in the area. </h1>  
</html>

```




## OUTPUT
![alt text](<Screenshot 2025-12-01 113122.png>)
![alt text](<Screenshot 2025-12-01 113028.png>)
![alt text](<Screenshot 2025-12-01 112821.png>)
![alt text](<Screenshot 2025-12-01 112324.png>)
![alt text](<Screenshot 2025-12-01 111823.png>)
![alt text](<Screenshot 2025-12-01 114522.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
