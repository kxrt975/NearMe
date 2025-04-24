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
```
map.html

<html>
    <head>
        <title>
            VIRUDHUNAGAR
        </title>
    </head>

    <body>
        <h1 align="center" style="background-color: violet; font-style: inherit 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">
            VIRUDHUNAGAR
        </h1>
        <h2 align="center" style="background-color: red;font-style: oblique;font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; color: steelblue;">
            Karthik padmanaban R - 212224110029
        </h2>\
        <img src="map.png" usemap="#MyCity" height="750" width="1411">
        <map name="MyCity">
            <area target="" alt="kamarajar house" title="kamarajar house" href="khouse.html" coords="515,520,657,448" shape="rect">
            <area target="" alt="museum" title="museum" href="museum.html" coords="992,614,1159,522" shape="rect">
            <area target="" alt="temple" title="temple" href="temple.html" coords="553,372,732,294" shape="rect">
            <area target="" alt="theatre" title="theatre" href="theatre.html" coords="683,266,852,200" shape="rect">
            <area target="" alt="turf" title="turf" href="turf.html" coords="1050,492,1249,440" shape="rect">
        </map>
    </body>
</html>

theatre.html

<html>
<head>
    <title>Rajalakshmi Theatre</title>
</head>
<body style="font-family: Arial, sans-serif; background-color: white; margin: 0; padding: 0; color: black">
    <header style="background: purple; color: white; padding: 20px; text-align: center;">
        <h1 style="margin: 0; font-size: 2.5rem;">Rajalakshmi Theatre</h1>
        <p style="font-size: 1rem; font-style: italic;">"ONE OF THE BEST THEATRE IN THE TOWN"</p>
    </header>
    <div style="max-width: 900px; margin: 20px auto; background: white; padding: 20px; border-radius: 8px; box-shadow: 0 4px 8px black(0, 0, 0, 0.1);">
        <h2 style="color: purple; margin-top: 0;">About Rajalakshmi Theatre</h2>
        <p>Rajalakshmi Theatre is a landmark entertainment destination, renowned for its state-of-the-art facilities and impeccable service. Located in the heart of the city, it has been a favorite for movie lovers for decades.</p>
        <p>This iconic theatre offers the perfect cinematic experience with high-definition screens, and luxurious seating. Designed to provide unmatched comfort, every aspect of the theatre ensures an immersive movie-watching experience.</p>
        <p>Whether you're a fan of blockbuster hits or independent films, Rajalakshmi Theatre brings the magic of movies to life. Its commitment to delivering exceptional entertainment has earned it a loyal audience and a reputation as one of the best theatres in the region.</p>
    </div>
</body>
</html>


turf.html

<html>
<head>
    <title>Kings Turf</title>
</head>
<body style="font-family: Arial, sans-serif; background-color: white; margin: 0; padding: 0; color: black">
    <header style="background: blue; color: white; text-align: center; padding: 20px;">
        <h1 style="margin: 0; font-size: 2.5rem;">Kings Turf</h1>
        <p style="font-size: 1rem;">"The best place for playing in our town"</p>
    </header>
    <div style="max-width: 800px; margin: 20px auto; background: white; padding: 20px; border-radius: 8px; box-shadow: 0 4px 6px black(0, 0, 0, 0.1);">
        <h2 style="color: blue;">About Kings Turf</h2>
        <p>Kings Turf is a high-quality sports field designed for various games like football, cricket, and more. It offers a smooth, safe, and durable playing surface for everyone.</p>
        <p>Kings Turf provides:  
            <ul style="margin: 10px 0; padding: 0 20px; list-style-type: square;">
                <li style="margin-bottom: 8px;">A well-maintained, professional-grade field.</li>
                <li style="margin-bottom: 8px;">More space for team sports and practice.</li>
                <li style="margin-bottom: 8px;">Affordable price for everyone.</li>
            </ul>
        </p>
    </div>
</body>
</html>


temple.html

<html>
<head>
    <title>Mariamman Temple</title>
</head>
<body style="font-family: Arial, sans-serif; background-color: white; margin: 0; padding: 0; color: black; line-height: 1.6;">
    <header style="background: orangered; color: white; text-align: center; padding: 20px;">
        <h1 style="margin: 0; font-size: 2.5rem;">Mariamman Temple</h1>
        <p style="font-size: 1rem;">"A BIGGEST TEMPLE IN TOWN"</p>
    </header>
    <div style="max-width: 800px; margin: 20px auto; background: white; padding: 20px; border-radius: 8px; box-shadow: 0 4px 6px black(0, 0, 0, 0.1);">
        <h2 style="color: orangered;">About the Temple</h2>
        <p>The Mariamman Temple is dedicated to Goddess Mariamman, the deity of rain and fertility. It is a sacred place for worshippers seeking blessings for health, prosperity, and protection.</p>
        <p>The temple is known for:  
            <ul style="margin: 10px 0; padding: 0 20px; list-style-type: square;">
                <li style="margin-bottom: 8px;">Beautifully decorated sanctum with vibrant colors.</li>
                <li style="margin-bottom: 8px;">Peaceful surroundings for prayer and meditation.</li>
                <li style="margin-bottom: 8px;">Annual festivals that attract devotees from far and wide.</li>
            </ul>
        </p>
    </div>
</body>
</html>


khouse.html

<html>
<head>
    <title>Kamarajar House</title>
</head>
<body style="font-family: Arial, sans-serif; background-color: white; margin: 0; padding: 0; color: black; line-height: 1.6;">
    <header style="background: blue; color: white; text-align: center; padding: 20px;">
        <h1 style="margin: 0; font-size: 2.5rem;">Kamarajar House</h1>
        <p style="font-size: 1rem;">"A Tribute to the King Maker"</p>
    </header>
    <div style="max-width: 800px; margin: 20px auto; background: white; padding: 20px; border-radius: 8px; box-shadow: 0 4px 6px black(0, 0, 0, 0.1);">
        <h2 style="color: blue;">About Kamarajar House</h2>
        <p>Kamarajar House is a memorial dedicated to K. Kamaraj, the "Kingmaker" and former Chief Minister of Tamil Nadu. It showcases his life, achievements, and dedication to public service.</p>
        <p>The house :  
            <ul style="margin: 10px 0; padding: 0 20px; list-style-type: square;">
                <li style="margin-bottom: 8px;">Photographs and personal belongings of Kamarajar.</li>
                <li style="margin-bottom: 8px;">Exhibits that depict his simple lifestyle and impactful leadership.</li>
                <li style="margin-bottom: 8px;">A library with books about his life and Indian politics.</li>
            </ul>
        </p>
    </div>
</body>
</html>


museum.html

<html>
<head>
    <title>Virudhunagar Government Museum</title>
</head>
<body style="font-family: Arial, sans-serif; background-color: white; margin: 0; padding: 0; color: black; line-height: 1.6;">
    <header style="background: green; color: white; text-align: center; padding: 20px;">
        <h1 style="margin: 0; font-size: 2.5rem;">Virudhunagar Government Museum</h1>
        <p style="font-size: 1rem;">"History and Culture of Tamil Nadu"</p>
    </header>
    <div style="max-width: 800px; margin: 20px auto; background: white; padding: 20px; border-radius: 8px; box-shadow: 0 4px 6px black(0, 0, 0, 0.1);">
        <h2 style="color: green;">About the Museum</h2>
        <p>The Virudhunagar Government Museum is a treasure trove of history, showcasing artifacts that reflect Tamil Nadu's rich cultural heritage. It is an educational and inspiring destination for history enthusiasts.</p>
        <p>The museum features:  
            <ul style="margin: 10px 0; padding: 0 20px; list-style-type: square;">
                <li style="margin-bottom: 8px;">Ancient sculptures and inscriptions.</li>
                <li style="margin-bottom: 8px;">Traditional handicrafts and tools.</li>
                <li style="margin-bottom: 8px;">Rare coins and historical artifacts.</li>
            </ul>
        </p>
    </div>
</body>
</html>
```

## OUTPUT

![Screenshot (10)](https://github.com/user-attachments/assets/16a78ff9-9963-411d-bc42-860fc92d9072)
![Screenshot (11)](https://github.com/user-attachments/assets/d6ad6ff0-54b9-4190-8ae9-bd40c9af69e2)
![Screenshot (12)](https://github.com/user-attachments/assets/8952e2b3-93fa-4280-b3d3-a5416786dbe9)
![Screenshot (13)](https://github.com/user-attachments/assets/77c849b9-7f3d-4498-86ec-0f2fca04680f)
![Screenshot (14)](https://github.com/user-attachments/assets/298eaf63-b5c2-49a0-84c8-ddffb417933c)
![Screenshot (15)](https://github.com/user-attachments/assets/e80456c6-007a-48c7-8983-f37e791dadda)

## RESULT
The program for implementing image maps using HTML is executed successfully.
