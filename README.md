# Ex03 Places Around Me
## Date: 

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

html>
    <head>
        <title>Thanjavur Big Temple</title>
    </head>
    <body bgcolor="Blue">
        The Brihadeeswarar Temple, or Thanjavur Big Temple, is an 11th-century Shaivite marvel built by Chola <br>
        emperor Raja Raja Chola I, renowned for its towering 216-foot vimana, massive granite construction, <br>
        intricate sculptures, and cultural and religious significance.<br>
        <br>
        The Brihadeeswarar Temple is part of the UNESCO World Heritage group “Great Living Chola Temples”, <br>
        along with Gangaikonda Cholapuram and Airavatesvara temples . Its architectural innovations, grandeur,<br>
        and cultural value have influenced South Indian temple design for centuries, marking it as a symbol<br>
        of Tamil heritage and the engineering prowess of the Chola dynasty. <br>
        <br>
        Visiting the temple is not just a spiritual experience but also a profound engagement with the artistic,<br>
        historical, and cultural zenith of medieval South India.
    </body>
</html>

manimandabam.html

<html>
    <head>
        <title>Raja Raja Cholan Manimandapam</title>

    </head>
    <body bgcolor="HotBlue">
        Rajarajan Manimandapam serves as an educational, cultural, and recreational site in Thanjavur,<br>
        celebrating the legacy of Raja Raja Chola I through its architecture, museum collections, and <br>
        landscaped surroundings. It is a must-visit destination for anyone interested in Tamil history <br>
        and Chola heritage.<br>
        <br>
        Rajarajan Manimandapam is located in the Southern Part of Thanjavur. It was built in 1991 during<br>
        the 8th World Tamil Conference. It is a beautiful structure and is built in the style of the <br>
        buildings constructed during the Chola period.<br>
        <br>
    </body>
</html>

marathaPalace.html

<html>
    <head>
        <title>Maratha Palace</title>
    </head>
    <body bgcolor="fuchsia">
        The Thanjavur Maratha Palace, also known as the Nayak Palace, is a historic monument in Thanjavur,<br>
        Tamil Nadu, India. Originally constructed by Nayak rulers in the 16th century, it was later expanded <br>
        by Maratha rulers in the 17th century. The palace served as the official residence of the Bhonsle<br>
        Maratha dynasty from 1674 to 1855.<br>
        <br>

        Construction began under Nayak king Sevappa Nayak and was completed by his successors. The<br>
        Maratha rulers, originally from Maharashtra, later took control and made significant architectural<br>
        additions. The palace complex encompasses multiple buildings, courtyards, and gardens.<br>
        <br>

        Its architecture blends Dravidian and Maratha styles, featuring intricate carvings, ornate pillars,<br>
        and grand arches. A museum within the palace displays artifacts including royal regalia, weaponry,<br>
        paintings, and sculptures. Recognized as a protected monument by the Archaeological Survey of India,<br>
         the Thanjavur Maratha Palace represents the region’s rich cultural and architectural heritage.<br>

    </body>

</html>

NHRC.html

<html>
    <head>
        <title> National Hospital Research Center</title>
    </head>
    <body bgcolor="teal">
            National Hospital Research Centre, also referred to as National Pharma Hospital and <br>
            Research Institute, is a multi-specialty hospital in Thanjavur, providing comprehensive<br>
            medical services with a high standard of care.<br>
            <br>
            The hospital has been serving the Thanjavur region since 2010, inaugurated officially in<br> 
            January 2011. It was founded by Rtn. F. Hajee L. Kamal Batcha, leveraging experience from<br>
            pharmaceutical ventures to establish a state-of-the-art healthcare facility. The hospital <br>
            functions on a large, green campus and provides tertiary care with infrastructure <br>
            comparable to corporate hospitals.<br>
            <br> 
    </body>
</html>

AnnaNagar.html

<html>
    <head>
        <title>Anna Nagar</title>
    </head>
    <body bgcolor="Lime">
        Anna Nagar is situated within Thanjavur district and can also refer to a small village/hamlet <br>
        in Tiruvidaimarudur Block under Thirumanalakudi Panchayath, approximately 51 km east of Thanjavur<br>
        city and 282 km from Chennai. The village is about 8 km from Tiruvidaimarudur town. It shares<br>
        proximity with other localities such as Kondangudiillam, Karna Kollai Agraharam, Melacavery,<br>
        Arul Nagar, and Kamaraj Nagar.<br>
        <br>
        Anna Nagar is ideal for individuals or families looking for a residential area with access to <br>
        reputable schools, healthcare facilities, and local markets, combined with available real <br>
        estate options ranging from small plots to larger independent houses and villas in Thanjavur.<br>
    </body>
</html>

```

## OUTPUT

![alt text](<Screenshot (37).png>)

![alt text](<Screenshot (38).png>)

![alt text](<Screenshot (39).png>)

![alt text](<Screenshot (40).png>)

![alt text](<Screenshot (41).png>)

![alt text](<Screenshot (42).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
