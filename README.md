# Ex03 Places Around Me
## Date: 05.12.2025

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
        <title>My City</title>
        <br>
        <br>
    </head>
    <body align="center">
        <h1 style="color:rgb(232, 17, 17)"><b>THANJAVUR-(THANJAI)</b></h1>
        <br>
        <h2 style="color: rgb(244, 149, 7);"><b>SABARINATHAN A-(25005972)</b></h2>

        <img src="Screenshot 2025-11-28 112912.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Thanjavur Big Temple" title="Thanjavur Big Temple" href="bigtemple.html" coords="823,418,898,488" shape="rect">
    <area target="" alt="Maratha Palace" title="Maratha Palace" href="marathaPalace.html" coords="907,320,96" shape="circle">
    <area target="" alt="Raja Raja  Cholan Manimandapam" title="Raja Raja  Cholan Manimandapam" href="manimandabam.html" coords="852,540,830,562,688,625,771,764,881,635,873,577,866,554,862,535,842,554" shape="poly">
    <area target="" alt="National Hospital Research Centre " title="National Hospital Research Centre " href="NHRC.html" coords="1321,85,1514,200" shape="rect">
    <area target="" alt="Anna Nagar" title="Anna Nagar" href="AnnaNagar.html" coords="1013,586,1087,577,1099,616,1268,743,1314,806,1248,904,1006,907" shape="poly">
</map>
    </body>
</html>

bigtemple.html

<html>
    <head>
        <title>Thanjavur Big Temple</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">
            <font color="red"><b>Thanjavur City</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Thanjavur Big Temple</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                The Brihadeeswarar Temple, or Thanjavur Big Temple, is an 11th-century Shaivite marvel built by Chola 
        emperor Raja Raja Chola I, renowned for its towering 216-foot vimana, massive granite construction,
        intricate sculptures, and cultural and religious significance.<br>
        <br>
        The Brihadeeswarar Temple is part of the UNESCO World Heritage group “Great Living Chola Temples”,
        along with Gangaikonda Cholapuram and Airavatesvara temples . Its architectural innovations, grandeur,
        and cultural value have influenced South Indian temple design for centuries, marking it as a symbol
        of Tamil heritage and the engineering prowess of the Chola dynasty. 
        <br>
        Visiting the temple is not just a spiritual experience but also a profound engagement with the artistic,
        historical, and cultural zenith of medieval South India.
         </p>
    </body>
</html>

manimandabam.html

<html>
    <head>
        <title>Rajarajan Manimandapam</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="red"><b>Thanjavur City</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Rajarajan Manimandapam</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                Rajarajan Manimandapam serves as an educational, cultural, and recreational site in Thanjavur,
        celebrating the legacy of Raja Raja Chola I through its architecture, museum collections, and 
        landscaped surroundings. It is a must-visit destination for anyone interested in Tamil history 
        and Chola heritage.<br>
        <br>
        Rajarajan Manimandapam is located in the Southern Part of Thanjavur. It was built in 1991 during
        the 8th World Tamil Conference. It is a beautiful structure and is built in the style of the 
        buildings constructed during the Chola period.
         </p>
    </body>
</html>

marathaPalace.html

<html>
    <head>
        <title>Thanjavur Maratha Palace</title>
    </head>
    <body bgcolor="hotpink">
        <h1 align="center">
            <font color="red"><b>Thanjavur City</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Thanjavur Maratha Palace</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                The Thanjavur Maratha Palace, also known as the Nayak Palace, is a historic monument in Thanjavur,
        Tamil Nadu, India. Originally constructed by Nayak rulers in the 16th century, it was later expanded 
        by Maratha rulers in the 17th century. The palace served as the official residence of the Bhonsle
        Maratha dynasty from 1674 to 1855.
        <br>

        Construction began under Nayak king Sevappa Nayak and was completed by his successors. The
        Maratha rulers, originally from Maharashtra, later took control and made significant architectural
        additions. The palace complex encompasses multiple buildings, courtyards, and gardens.
        
         </p>
    </body>
</html>

NHRC.html

<html>
    <head>
        <title>National Hospital Research Centre</title>
    </head>
    <body bgcolor="skyblue">
        <h1 align="center">
            <font color="red"><b>Thanjavur City</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>National Hospital Research Centre</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                National Hospital Research Centre, also referred to as National Pharma Hospital and 
            Research Institute, is a multi-specialty hospital in Thanjavur, providing comprehensive
            medical services with a high standard of care.
            <br>
            The hospital has been serving the Thanjavur region since 2010, inaugurated officially in
            January 2011. It was founded by Rtn. F. Hajee L. Kamal Batcha, leveraging experience from
            pharmaceutical ventures to establish a state-of-the-art healthcare facility. The hospital 
            functions on a large, green campus and provides tertiary care with infrastructure 
            comparable to corporate hospitals.
         </p>
    </body>
</html>

AnnaNagar.html

<html>
    <head>
        <title>Anna Nagar</title>
    </head>
    <body bgcolor="aqua">
        <h1 align="center">
            <font color="red"><b>Thanjavur City</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>Anna Nagar</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="Georgia" size="5">
                Anna Nagar is situated within Thanjavur district and can also refer to a small village/hamlet 
        in Tiruvidaimarudur Block under Thirumanalakudi Panchayath, approximately 51 km east of Thanjavur
        city and 282 km from Chennai. The village is about 8 km from Tiruvidaimarudur town. It shares
        proximity with other localities such as Kondangudiillam, Karna Kollai Agraharam, Melacavery,
        Arul Nagar, and Kamaraj Nagar.
        <br>
        Anna Nagar is ideal for individuals or families looking for a residential area with access to
        reputable schools, healthcare facilities, and local markets, combined with available real
        estate options ranging from small plots to larger independent houses and villas in Thanjavur.
    
            </p>
    </body>
</html>

```

## OUTPUT

![alt text](<Screenshot (46).png>)

![alt text](<Screenshot (45).png>)

![alt text](<Screenshot (47).png>)

![alt text](<Screenshot (48).png>)

![alt text](<Screenshot (49).png>)

![alt text](<Screenshot (50).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
