# Ex04 Places Around Me
## Date:5/10/2024

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
        <title>MAP APP</title>
    </head>
    <body>
        <h1 align="center">KANCHIPURAM</h1>
        <h2 align="center"> ROHAN J (212223040171)</h2>
        <center>
            <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-05-10 133417.png" height="600"width="1000"
">

            <map name="image-map">
                <area  alt="EKAMBARANATHAR TEMPLE" title="" href="temple1.html" coords="662,557,295,643" shape="rect">
                <area  alt="KAMAKSHI AMMAN TEMPLE" title="KAMAKSHI AMMAN TEMPLE" href="temple2.html" coords="761,224,82" shape="circle">
                <area  alt="kAILASANATHAR TEMPLE"  title="Alagar Public School" href="temple3.html" coords="869,726,1010,704,1069,729,1001,757,937,757" shape="poly">
                <area  alt="A.S.BABU SHAH" title="A.S.BABU SHAH" href="textile.html" coords="600,362,97" shape="circle">
                <area  alt="BABU CINEMAS" title="BABU CINEMAS" href="cinemas.html" coords="865,394,1042,468" shape="rect">
</center>
</map>
    </body>
</html>

temple1.html
<html>
<head>
<h1><center>KANCHIPURAM</center></h1>
<h3><center>EKAMBARANATHAR TEMPL</center></h3>
<hr>
</head>
<body bgcolor="GREEN">
<p>
    The Ekambareswarar Temple, also known as Ekambaranathar Temple, is an ancient Hindu temple nestled in the sacred city of Kanchipuram, Tamil Nadu, India. This majestic temple, steeped in history and spirituality, is dedicated to Lord Shiva, the Supreme Being in Hinduism. Renowned for its architectural grandeur and spiritual significance, the Ekambareswarar Temple stands as a testament to the rich cultural heritage of South India. Its sprawling complex encompasses towering gopurams adorned with intricate sculptures, vast courtyards, and serene ponds. One of the most striking features of the temple is the massive lingam, the symbol of Lord Shiva, worshipped here as Ekambareswarar. 
</body>
</html>

temple2.html
<html>
<head>
<h1><center>KANCHIPURAM</center></h1>
<h3><center>KAMAKSHI AMMAN TEMPLE</center></h3>
<hr>
</head>
<body bgcolor="blue">
<p>
    The Kamakshi Amman Temple, situated in the bustling town of Kanchipuram, Tamil Nadu, India, stands as a beacon of devotion and divine grace. Dedicated to Goddess Kamakshi, an incarnation of Goddess Parvati, this ancient temple holds a significant place in Hindu mythology and spiritual tradition. Adorned with ornate architecture typical of South Indian temple design, the Kamakshi Amman Temple captivates visitors with its towering gopurams (temple towers), intricately carved pillars, and serene inner sanctums. Devotees flock to the temple to seek the blessings of Goddess Kamakshi, believed to be the embodiment of divine feminine energy and the bestower of boons and blessings. The sanctum sanctorum houses the divine idol of Kamakshi Amman, adorned with exquisite jewelry and garlands, radiating an aura of peace and serenity. Throughout the year, the temple resonates with the melodious chants of hymns and the fragrance of sacred offerings, creating an atmosphere charged with spiritual energy. Festivals such as Navaratri, dedicated to the worship of the Divine Mother, are celebrated with great fervor, drawing pilgrims and devotees from far and wide. With its timeless beauty and profound spiritual significance, the Kamakshi Amman Temple continues to inspire reverence and devotion, serving as a sacred abode where devotees find solace and divine grace.

</p>
</body>
</html>

temple3.html
<html>
<head>
<h1><center>KANCHIPURAM</center></h1>
<h3><center>kAILASANATHAR TEMPLE</center></h3>
<hr>
</head>
<body bgcolor="Purple">
<p>
    The Kailasanathar Temple, nestled amidst the serene landscapes of Kanchipuram, Tamil Nadu, India, stands as a magnificent testament to the architectural brilliance and spiritual devotion of ancient India. Built in the 8th century CE by the Pallava dynasty, this temple is renowned as one of the oldest structures in Kanchipuram and represents a quintessential example of Dravidian architecture. Dedicated to Lord Shiva, the temple exudes a sense of grandeur with its intricately carved pillars, majestic vimana (tower) adorned with exquisite sculptures, and sprawling courtyards that echo with the chants of devotees. The sanctum sanctorum houses the presiding deity, Lord Kailasanathar, in the form of a lingam, symbolizing the cosmic presence of Shiva. Surrounding the main shrine are numerous smaller shrines dedicated to various deities, adding to the spiritual aura of the temple complex. Visitors marvel at the intricate carvings depicting scenes from Hindu mythology, celestial beings, and intricate patterns adorning the walls and ceilings of the temple. Despite the passage of centuries, the Kailasanathar Temple stands as a timeless testament to India's rich cultural heritage and continues to inspire awe and reverence among pilgrims and tourists alike, beckoning them to experience the divine presence of Lord Shiva in this sacred abode.
</p>
</body>
</html>

textile.html
<html>
<head>
<h1><center>KANCHIPURAM</center></h1>
<H1><CENTER>A.S.BABU SHAH</CENTER></H1>

<hr>
</head>
<body bgcolor="red">
<p>
    A.S. Babu Shah was a prominent figure in Kanchipuram, Tamil Nadu, India, known for his contributions to the local community and society at large. His legacy transcended regional boundaries, impacting various spheres of life in Kanchipuram and beyond. A philanthropist at heart, Babu Shah dedicated himself to numerous charitable endeavors aimed at uplifting the underprivileged and supporting educational initiatives. His unwavering commitment to social welfare earned him respect and admiration from all walks of life. Babu Shah's presence in Kanchipuram was synonymous with compassion and generosity, as he tirelessly worked towards the betterment of society. Whether through educational scholarships, healthcare initiatives, or community development projects, his impact was deeply felt and widely appreciated. 
</p>
</body>
</html>

cinemas.html
<html>
<head>
<h1><center>KANCHIPURAM</center></h1>
<h3><center>BABU CINEMAS</center></h3>
<hr>
</head>
<body bgcolor="PINK">
<p>
    Babu Cinemas in Kanchipuram stands as a premier entertainment destination, renowned for its cutting-edge facilities and commitment to delivering unparalleled cinematic experiences. From its inviting lobby adorned with vibrant posters to its state-of-the-art audiovisual technology and comfortable seating arrangements, Babu Cinemas ensures a memorable viewing journey for movie enthusiasts. Beyond its role as a multiplex, Babu Cinemas serves as a cultural landmark, fostering a sense of community among diverse audiences through its eclectic programming and dedication to showcasing both mainstream blockbusters and independent films. Whether seeking escapism, inspiration, or simply a night out with loved ones, Babu Cinemas offers a welcoming atmosphere where patrons can immerse themselves in the magic of the silver screen.
</p>
</body>
</html>


```

## OUTPUT
![Screenshot 2024-05-10 143034](https://github.com/Rohanjeyachandiran/NearMe/assets/161102491/29cbbcc4-6274-4feb-b031-23382e4ff63f)
![Screenshot 2024-05-10 141002](https://github.com/Rohanjeyachandiran/NearMe/assets/161102491/ee47f40d-5234-4a01-b46e-e90250ab3939)
![Screenshot 2024-05-10 141030](https://github.com/Rohanjeyachandiran/NearMe/assets/161102491/ca4a33f5-058d-4acf-b7f3-7333a371580b)
![Screenshot 2024-05-10 141134](https://github.com/Rohanjeyachandiran/NearMe/assets/161102491/5dc70d59-0711-4b62-b398-356d150743ab)
![Screenshot 2024-05-10 141210](https://github.com/Rohanjeyachandiran/NearMe/assets/161102491/bb03d449-db62-44ae-aa9e-df2779d50baa)
![Screenshot 2024-05-10 141233](https://github.com/Rohanjeyachandiran/NearMe/assets/161102491/4d0c209c-65a4-473c-a2a8-b546c320e251)









## RESULT
The program for implementing image maps using HTML is executed successfully.
