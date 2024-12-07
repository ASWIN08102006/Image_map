Ex04 Places Around Me
# Date: 4/11/2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
Image Map.html
<!DOCTYPE html>
<html>
<head>
    
    <title>Image Map</title>
</head>
<body>
    <center>
    <h1> My Native - Chidamabaram</h1>
    <h2> Experience My Beautiful Town</h2></center>
    <center>

<img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-06 105022.png" usemap="#image-map"></center>
<map name="image-map">
    <img src="Screenshot 2024-12-06 105022.png" usemap="#image-map">
<map name="image-map">
    <area alt="Thillai Natarajar Temple" title="Thillai Natarajar Temple" href="C:\Users\admin\Desktop\HTML\Sub Codes\Thillai Natarajar Temple.html" coords="526,336,773,395" shape="rect"></area>
    <area alt="Pichavaram" title="Pichavaram" href="C:\Users\admin\Desktop\HTML\Sub Codes\Pichavaram.html" coords="877,260,995,310" shape="rect"></area>
    <area alt="Kodiyampalayam Beach" title="Kodiyampalayam Beach" href="C:\Users\admin\Desktop\HTML\Sub Codes\Kodiyampalayam Beach.html" coords="930,407,1168,453" shape="rect"></area>
    <area alt="Kollidam River" title="Kollidam River" href="C:\Users\admin\Desktop\HTML\Sub Codes\Kollidam River.html" coords="617,696,756,744" shape="rect"></area>
</map>



</body>
</html>

Thillai Natarajar Temple.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Thillai Natarajar Temple in Chidambaram - A Sacred Shrine of Lord Shiva">
    <title>Thillai Natarajar Temple - Chidambaram</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            background-color: #34495e;
            padding: 10px 0;
            text-align: center;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            font-size: 16px;
        }

        nav a:hover {
            background-color: #1abc9c;
        }

        section {
            padding: 20px;
            margin: 20px;
        }

        .content {
            display: flex;
            justify-content: space-between;
        }

        .content div {
            width: 48%;
        }

        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            margin: 10px 0;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        .cta-button {
            background-color: #1abc9c;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
        }

        .cta-button:hover {
            background-color: #16a085;
        }

        .history img {
            width: 100%;
            border-radius: 10px;
        }

        .about h2, .history h2 {
            color: #1abc9c;
        }
    </style>
</head>

<body>

    <header>
        <h1>Thillai Natarajar Temple, Chidambaram</h1>
        <p>A Sacred Shrine of Lord Shiva in Tamil Nadu, India</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#history">History</a>
        <a href="#significance">Significance</a>
        <a href="#architecture">Architecture</a>
        <a href="#gallery">Gallery</a>
    </nav>

    <section id="about" class="about">
        <h2>About the Temple</h2>
        <p>The Thillai Natarajar Temple, also known as the Chidambaram Natarajar Temple, is a famous Hindu temple dedicated to Lord Shiva. It is located in the town of Chidambaram, Tamil Nadu, and is one of the five major temples of Shiva in Tamil Nadu, representing the element of Ether (Akasha).</p>
        <p>The temple is known for its rich history, stunning architecture, and spiritual significance, making it one of the most revered temples in India.</p>
    </section>

    <section id="history" class="history">
        <h2>History</h2>
        <p>The Thillai Natarajar Temple has been an important center of worship since ancient times. It is believed that the temple's history dates back to the 2nd century BCE, and it was expanded and renovated over the centuries. The temple was originally under the rule of the Chola dynasty, and many of the temple's present structures were constructed during their reign.</p>
        <div class="content">
            <div>
                <h3>Historical Legends</h3>
                <p>According to legend, Lord Shiva danced the Ananda Tandava (the dance of bliss) in this temple. The dance symbolizes the creation, preservation, and destruction of the universe. It is also believed that the temple was the site where the cosmic dance of Lord Shiva was first performed.</p>
            </div>
            <div>
                <h3>Renovations and Expansion</h3>
                <p>Over the centuries, the temple has undergone numerous renovations. King Kulothunga Chola I, who ruled during the 12th century, is credited with much of the temple's current architecture and grandeur.</p>
            </div>
        </div>
    </section>

    <section id="significance" class="significance">
        <h2>Significance</h2>
        <p>The Thillai Natarajar Temple holds immense spiritual and cultural importance. It is considered the center of the universe, where the divine dance of creation, preservation, and destruction takes place. The temple is also a major pilgrimage site for Shaivites and attracts thousands of devotees annually.</p>
        <p>It is one of the few temples where Lord Shiva is depicted in the form of Nataraja, the cosmic dancer, symbolizing the infinite cycle of creation and destruction.</p>
    </section>

    <section id="architecture" class="architecture">
        <h2>Architecture</h2>
        <p>The temple's architecture is an exquisite example of Dravidian style. The main sanctum, which houses the deity of Lord Nataraja, is surrounded by multiple halls and towers. The most famous of these is the thousand-pillar hall, which has intricate carvings and sculptures depicting scenes from Hindu mythology.</p>
        <p>The temple complex also has four large gopurams (gateway towers) at each entrance, adorned with colorful sculptures of deities, mythological figures, and animals.</p>
    </section>

    <section id="gallery" class="gallery">
        <h2>Gallery</h2>
        <div class="content">
            <div>
                <img src="C:\Users\admin\Desktop\HTML\Images\thillai-natraja-with-shivganga.webp"alt="Thillai Natarajar Temple View">
                <img src="C:\Users\admin\Desktop\HTML\Images\gold-roof-temple-2.webp" alt="Lord Nataraja gold roof">
            </div>
            <div>
                <img src="C:\Users\admin\Desktop\HTML\Images\images.jpeg" alt="1000 pillar Hall">
                <img src="C:\Users\admin\Desktop\HTML\Images\9134305361_5e63e800e1_h.jpg" alt="Car festival">
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Thillai Natarajar Temple. All rights reserved.</p>
        <a href="#about" class="cta-button">Learn More</a>
    </footer>

</body>

</html>

Pichavaram.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Pichavaram Mangrove Forest in Cuddalore District, Tamil Nadu - A Serene Destination">
    <title>Pichavaram, Cuddalore District</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            background-color: #34495e;
            padding: 10px 0;
            text-align: center;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            font-size: 16px;
        }

        nav a:hover {
            background-color: #1abc9c;
        }

        section {
            padding: 20px;
            margin: 20px;
        }

        .content {
            display: flex;
            justify-content: space-between;
        }

        .content div {
            width: 48%;
        }

        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            margin: 10px 0;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        .cta-button {
            background-color: #1abc9c;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
        }

        .cta-button:hover {
            background-color: #16a085;
        }

        .history img {
            width: 100%;
            border-radius: 10px;
        }

        .about h2, .history h2, .tourist-attractions h2 {
            color: #1abc9c;
        }
    </style>
</head>

<body>

    <header>
        <h1>Pichavaram Mangrove Forest, Cuddalore</h1>
        <p>A Hidden Gem of Tamil Nadu</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#location">Location</a>
        <a href="#history">History</a>
        <a href="#significance">Significance</a>
        <a href="#tourist-attractions">Tourist Attractions</a>
        <a href="#gallery">Gallery</a>
    </nav>

    <section id="about" class="about">
        <h2>About Pichavaram</h2>
        <p>Pichavaram is one of the largest mangrove forests in India, located in the Cuddalore district of Tamil Nadu. Known for its serene beauty, it features a labyrinth of narrow channels, rivers, and islands, offering a picturesque view of nature. The mangrove forest is home to a variety of wildlife, including numerous species of birds and marine life.</p>
        <p>This ecological wonder is often referred to as the "Venice of the East" because of its waterways and lush green landscapes. It is a must-visit destination for nature lovers and eco-tourists.</p>
    </section>

    <section id="location" class="location">
        <h2>Location</h2>
        <p>Pichavaram is situated approximately 16 kilometers from Chidambaram, in the Cuddalore district of Tamil Nadu. It lies along the coastline of the Bay of Bengal, making it easily accessible via road. The nearest railway station is in Chidambaram, and the nearest airport is in Pondicherry, about 60 kilometers away.</p>
    </section>

    <section id="history" class="history">
        <h2>History</h2>
        <p>The Pichavaram Mangrove Forest has a rich history, with its existence dating back centuries. It has been a key part of the region's ecosystem, providing a habitat for numerous species of flora and fauna. Historically, the region has been a source of livelihood for local communities, who rely on fishing and salt production.</p>
        <p>The forest is also of ecological importance as it helps protect the coastal areas from erosion, making it an invaluable part of the environment.</p>
        <div class="content">
            <div>
                <h3>Ecological Importance</h3>
                <p>The mangrove ecosystem of Pichavaram plays a critical role in coastal protection, reducing the impact of storms and tsunamis, and maintaining biodiversity. The forest acts as a nursery for fish and a feeding ground for migratory birds.</p>
            </div>
            <div>
                <h3>Local Communities</h3>
                <p>Many local communities have lived in and around Pichavaram for generations. These communities depend on the forest for their livelihoods, particularly through fishing and the collection of firewood and other natural resources. Their deep connection with the land has shaped the cultural and ecological heritage of the region.</p>
            </div>
        </div>
    </section>

    <section id="significance" class="significance">
        <h2>Significance of Pichavaram</h2>
        <p>Pichavaram is not just a natural wonder but also holds great significance for the state of Tamil Nadu and India. It is an important bird-watching destination and a hotspot for biodiversity. The forest is home to more than 200 species of birds, making it a paradise for birdwatchers and photographers.</p>
        <p>Additionally, Pichavaram’s rich ecosystem plays a vital role in maintaining the balance of the coastal environment. It is recognized as an environmentally significant site and is part of the larger effort to conserve India’s unique mangrove ecosystems.</p>
    </section>

    <section id="tourist-attractions" class="tourist-attractions">
        <h2>Tourist Attractions</h2>
        <ul>
            <li><strong>Boat Ride Through Mangroves:</strong> Visitors can take boat rides through the narrow waterways of the mangrove forest, offering a unique way to explore the natural beauty.</li>
            <li><strong>Bird Watching:</strong> The forest is home to many species of migratory and native birds. Pichavaram is an excellent destination for birdwatching.</li>
            <li><strong>Wildlife Photography:</strong> The picturesque landscape and abundant wildlife make Pichavaram a great spot for photography enthusiasts.</li>
            <li><strong>Eco-Tourism:</strong> Pichavaram offers eco-friendly tourism experiences, where visitors can explore the mangroves while preserving the natural surroundings.</li>
        </ul>
    </section>

    <section id="gallery" class="gallery">
        <h2>Gallery</h2>
        <div class="content">
            <div>
                <img src="C:\Users\admin\Desktop\HTML\Images\pichavaram-mangrove-forest.jpg"alt="Pichavaram Mangrove Forest">
                <img src="C:\Users\admin\Desktop\HTML\Images\photo.avif" alt="Boat Ride in Pichavaram">
            </div>
            <div>
                <img src="C:\Users\admin\Desktop\HTML\Images\6.jpg" alt="Birds at Pichavaram">
                <img src="C:\Users\admin\Desktop\HTML\Images\1563792081_img_3267.jpg.webp" alt="Sunset at Pichavaram">
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Pichavaram, Cuddalore. All rights reserved.</p>
        <a href="#about" class="cta-button">Learn More</a>
    </footer>

</body>

</html>

Kodiyampalayam Beach.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Kodiyampalayam Beach - A Serene Destination in Tamil Nadu">
    <title>Kodiyampalayam Beach</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            background-color: #34495e;
            padding: 10px 0;
            text-align: center;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            font-size: 16px;
        }

        nav a:hover {
            background-color: #1abc9c;
        }

        section {
            padding: 20px;
            margin: 20px;
        }

        .content {
            display: flex;
            justify-content: space-between;
        }

        .content div {
            width: 48%;
        }

        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            margin: 10px 0;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        .cta-button {
            background-color: #1abc9c;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
        }

        .cta-button:hover {
            background-color: #16a085;
        }

        .about h2, .attractions h2 {
            color: #1abc9c;
        }
    </style>
</head>

<body>

    <header>
        <h1>Kodiyampalayam Beach</h1>
        <p>A Hidden Gem in Tamil Nadu</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#location">Location</a>
        <a href="#attractions">Attractions</a>
        <a href="#gallery">Gallery</a>
    </nav>

    <section id="about" class="about">
        <h2>About Kodiyampalayam Beach</h2>
        <p>Kodiyampalayam Beach is a serene and relatively unexplored beach located in the southern part of Tamil Nadu. Known for its calm and clear waters, golden sands, and peaceful environment, the beach is an ideal destination for those seeking a quiet retreat away from the hustle and bustle of city life.</p>
        <p>Though not as famous as some other beaches in Tamil Nadu, Kodiyampalayam Beach is growing in popularity among tourists looking for a tranquil coastal experience. Visitors can enjoy a range of activities including beach walks, photography, and exploring the nearby local villages.</p>
    </section>

    <section id="location" class="location">
        <h2>Location</h2>
        <p>Kodiyampalayam Beach is located in the Cuddalore district of Tamil Nadu, approximately 10 kilometers from the town of Cuddalore and 25 kilometers from Pondicherry. The beach can be easily accessed by road from the nearby towns and cities.</p>
        <p>The nearest railway station is Cuddalore, and the nearest airport is in Pondicherry, around 30 minutes away by car. The beach is a perfect getaway for tourists visiting the area.</p>
    </section>

    <section id="attractions" class="attractions">
        <h2>Attractions</h2>
        <p>Kodiyampalayam Beach offers a range of attractions for visitors looking to enjoy the natural beauty of the region. Here are some of the main attractions:</p>
        <ul>
            <li><strong>Peaceful Atmosphere:</strong> Unlike crowded beaches, Kodiyampalayam offers a serene and relaxing atmosphere, ideal for families, solo travelers, and couples looking to unwind.</li>
            <li><strong>Beach Walks:</strong> Enjoy long walks along the golden sandy beach, feeling the cool sea breeze and listening to the sound of the waves crashing on the shore.</li>
            <li><strong>Sunsets:</strong> The sunsets at Kodiyampalayam Beach are breathtaking, with the sun sinking into the horizon over the Bay of Bengal.</li>
            <li><strong>Photography:</strong> The stunning natural beauty of the beach and surrounding areas makes it a great place for photography, especially for nature and landscape enthusiasts.</li>
            <li><strong>Local Villages:</strong> Explore the nearby fishing villages, where you can learn about the local culture and lifestyle.</li>
        </ul>
    </section>

    <section id="gallery" class="gallery">
        <h2>Gallery</h2>
        <div class="content">
            <div>
                <img src="C:\Users\admin\Desktop\HTML\Images\sddefault.jpg" alt="Kodiyampalayam Beach">
                <img src="C:\Users\admin\Desktop\HTML\Images\maxresdefault.jpg" alt="Kodiyampalayam Beach Sunset">
            </div>
            <div>
                <img src="C:\Users\admin\Desktop\HTML\Images\7503241880_1b68542760_b.jpg" alt="Golden Sands of Kodiyampalayam">
                <img src="C:\Users\admin\Desktop\HTML\Images\kodiyampalayam-beach-new-beach-road-nagapattinam-tourist-attraction-jdbUfpiqTz.jpg" alt="Beach Walks at Kodiyampalayam">
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Kodiyampalayam Beach. All rights reserved.</p>
        <a href="#about" class="cta-button">Learn More</a>
    </footer>

</body>

</html>


Kollidam River.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Kollidam River, Chidambaram - A Majestic River in Tamil Nadu">
    <title>Kollidam River, Chidambaram</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            background-color: #34495e;
            padding: 10px 0;
            text-align: center;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            font-size: 16px;
        }

        nav a:hover {
            background-color: #1abc9c;
        }

        section {
            padding: 20px;
            margin: 20px;
        }

        .content {
            display: flex;
            justify-content: space-between;
        }

        .content div {
            width: 48%;
        }

        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            margin: 10px 0;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        .cta-button {
            background-color: #1abc9c;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
        }

        .cta-button:hover {
            background-color: #16a085;
        }

        .about h2, .attractions h2 {
            color: #1abc9c;
        }
    </style>
</head>

<body>

    <header>
        <h1>Kollidam River, Chidambaram</h1>
        <p>A Majestic River of Tamil Nadu</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#location">Location</a>
        <a href="#significance">Significance</a>
        <a href="#attractions">Attractions</a>
        <a href="#gallery">Gallery</a>
    </nav>

    <section id="about" class="about">
        <h2>About Kollidam River</h2>
        <p>The Kollidam River, also known as the Coleroon River, is a significant river in Tamil Nadu, India. It is a distributary of the Kaveri River, originating near the city of Trichy and flowing through the Chidambaram region. The river is known for its scenic beauty and is an important water source for agriculture in the region.</p>
        <p>The Kollidam River has been historically significant for the local people and the surrounding villages. It provides water for irrigation and is a major part of the region's economy. The river is also rich in biodiversity, offering a habitat to many species of birds, fish, and other aquatic life.</p>
    </section>

    <section id="location" class="location">
        <h2>Location</h2>
        <p>The Kollidam River flows through several districts in Tamil Nadu, including the Chidambaram region. The river is located about 20 km north of the town of Chidambaram, near the Bay of Bengal coast. It is an important river in the Cauvery River Basin and serves as a lifeline for the communities in this area.</p>
        <p>It flows through areas such as Kattumannar Koil and continues to merge with the Kaveri River. The river is easily accessible from Chidambaram by road and provides a beautiful landscape for visitors and locals alike.</p>
    </section>

    <section id="significance" class="significance">
        <h2>Significance of Kollidam River</h2>
        <p>The Kollidam River holds immense significance for the local communities, as it plays a crucial role in providing water for agriculture, drinking, and other essential needs. The river also contributes to the economic activities of the region, such as fishing and transportation. Its presence has shaped the local landscape and culture over centuries.</p>
        <p>Besides its utility, the river has cultural importance in the local communities. The Kollidam River is worshiped by many as a sacred body of water, and there are several temples located along its banks. The river also serves as a key waterway, supporting the livelihoods of many fishermen and other local residents.</p>
    </section>

    <section id="attractions" class="attractions">
        <h2>Attractions near Kollidam River</h2>
        <p>Kollidam River is not only significant for its practical uses but also offers several natural and cultural attractions for visitors. Here are some of the main attractions near the river:</p>
        <ul>
            <li><strong>Scenic Boat Rides:</strong> Tourists can enjoy peaceful boat rides along the Kollidam River, offering views of the lush green surroundings and the river's calm waters.</li>
            <li><strong>Bird Watching:</strong> The river is a hotspot for birdwatching, especially for migratory species, which visit the riverbanks in large numbers during certain seasons.</li>
            <li><strong>Temples Along the River:</strong> The Kollidam River is dotted with several ancient temples, such as the Kottaiyur Temple, which are historically and culturally significant.</li>
            <li><strong>Fishing Villages:</strong> Visit the nearby fishing villages to experience the local way of life and interact with the communities that rely on the river for their livelihood.</li>
        </ul>
    </section>

    <section id="gallery" class="gallery">
        <h2>Gallery</h2>
        <div class="content">
            <div>
                <img src="C:\Users\admin\Desktop\HTML\Images\Kollidam_River.jpeg" alt="Kollidam River Landscape">
                <img src="C:\Users\admin\Desktop\HTML\Images\kollidam-river.png.webp" alt="Boating in Kollidam River">
            </div>
            <div>
                <img src="C:\Users\admin\Desktop\HTML\Images\kollidam-river.png.webp" alt="Bird Watching near Kollidam River">
                <img src="C:\Users\admin\Desktop\HTML\Images\320-214-17046935-461-17046935-1669559866346.jpg" alt="Temple along Kollidam River">
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Kollidam River, Chidambaram. All rights reserved.</p>
        <a href="#about" class="cta-button">Learn More</a>
    </footer>

</body>

</html>


```
# OUTPUT
![Screenshot 2024-12-07 204754](https://github.com/user-attachments/assets/96649349-f3e6-40d0-8ca9-8b65f2ab55c7)

![Screenshot 2024-12-07 205048](https://github.com/user-attachments/assets/f9bfcb17-d70c-4d08-805b-c0e103b82fce)


![Screenshot 2024-12-07 205057](https://github.com/user-attachments/assets/9fb9b00d-c7ec-4068-9479-4d2b03a99395)

![Screenshot 2024-12-07 205114](https://github.com/user-attachments/assets/9edab7d5-be70-4339-86dc-5abd9c7391fc)

![Screenshot 2024-12-07 205124](https://github.com/user-attachments/assets/1b74ed70-f6c6-40ef-8c7f-23f5e89bb8f3)


# RESULT
The program for implementing image maps using HTML is executed successfully.




