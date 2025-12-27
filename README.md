# Ex.06 Restaurant Website
## Date:27/12/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<html>
    <head>
        <title>Admin - Le Boissy d'Anglas</title>
        <link href="style1.css" rel="stylesheet">
    </head>
    <body class="img1">
        <nav class="id1">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>
    <div class="box"><br><br>
        <font class="head"> ADMIN TEAM</font>
        <div class="row">
            <div class="admin">
                <img src="Screenshot 2025-12-27 133757.png">
                <div class="detail"><br>MESSI<br><font class="high">[CEO]</font></div>
            </div>
            <div class="admin">
                <img src="Screenshot 2025-12-27 133931.png">
                <div class="detail"><br>CRISTIANO<br><font class="high">[Manager]</font></div>
            </div>
            <div class="admin">
                <img src="Screenshot 2025-12-27 134000.png">
                <div class="detail"><br>NEYMAR<br><font class="high">[Operat Manager]</font></div>
            </div>
            <div class="admin">
                <img src="Screenshot 2025-12-27 134021.png">
                <div class="detail"><br>SUNIL CHHETRI<br><font class="high">[HR ]</font></div>
            </div>
            <div class="admin">
                <img src="Screenshot 2025-12-27 134459.png">
                <div class="detail"><br>MARADONA<br><font class="high">[Chef]</font></div>
            </div>
            <div class="admin">
                <img src="Screenshot 2025-12-27 134537.png">
                <div class="detail"><br>PELE<br><font class="high">[Asst Chef]</font></div>
            </div>
        </div>

    </div>
        <footer class="footer">
        &copy; ANURANJAN B (25003110)
    </footer>
    </body>
</html>


<html>
    <head>
        <title>Contact - Le Boissy d'Anglas</title>
        <link href="style2.css" rel="stylesheet">
    </head>
    <body class="img1">
        <nav class="id1">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>
    <div class="content">
        <h1 class="head">Contact Us</h1>
        <div class="info">
            <h2> located at Carrer d'Enric Granados 86-88</h2>
            <div>Barcelona</div>
            <div>45, Rue Boissy d'Anglas,</div>
            <div>Barcelona.20./565gkl</div>

            <h2>Phone:</h2>
            <div>5646446445654</div>

            <h2>Email:</h2>
            <div>bellavista@gmail.com</div>
        </div>
        <footer class="footer">
    &copy; ANURANJAN B (25003110)
        </footer> 
    </div>
    </body>
</html>


<html>
    <head>
        <title>Homepage - Le Boissy d'Anglas</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body class="img1">
        <nav class="id1">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>
    <div class="content">
        <h1 class="head">Bellavista del Jardin</h1>
        <font class="quote">"Food is our common ground, a universal experience"</font><br><br>
        <font class="info">this is restaurant which owns by lionel messi . A vibrant, village-themed restaurant opened with his family,featuring a wide menu.</font>      
        <div class="images">
            <img src="Screenshot 2025-12-25 223922.png" alt="Cafe Interior">
            <img src="Screenshot 2025-12-25 223941.png" alt="Coffee and Pastries">
        </div>
        <footer class="footer">
    &copy; ANURANJAN B [25003110]
        </footer> </div>
</body>
</html>
    </body>
</html>

<html>
    <head>
        <title>Menu - Le Boissy d'Anglas</title>
        <link href="style3.css" rel="stylesheet">
    </head>
    <body class="img1">
        <nav class="id1">
        <a href="home.html">HOME</a>
        <a href="menu.html">MENU</a>
        <a href="admin.html">ADMIN</a>
        <a href="contact.html">CONTACT</a>
    </nav>
    <div class="box"><br><br>
        <font class="head">MENU</font>
        <div class="row">
            <div class="food">
                <img src="Screenshot 2025-12-27 143458.png">
                <div class="detail"><br>Organic eggs with mayonnaise<br><font class="high">$ 10.8</font></div>
            </div>
            <div class="food">
                <img src="Screenshot 2025-12-27 143447.png">
                <div class="detail"><br>Rustic meat spread<br><font class="high">$ 13.2</font></div>
            </div>
            <div class="food">
                <img src="Screenshot 2025-12-27 143422.png">
                <div class="detail"><br>Filet de hareng, pomme tiede<br><font class="high">$ 18.5</font></div>
            </div>
            <div class="food">
                <img src="Screenshot 2025-12-27 143411.png">
                <div class="detail"><br>Ice cream sundaes<br><font class="high">$ 13</font></div>
            </div>
            <div class="food">
                <img src="Screenshot 2025-12-27 143359.png"detail"><br>Charcuterie board (assorted cured meats)<br><font class="high">$ 28</font></div>
            </div>
           
                
        </div>

    </div>
        <footer class="footer">
        &copy; ANURANJAN B (25003110)
    </footer>
    </body>
</html>


.img1
{
    background-image: url('Screenshot 2025-12-25 220130.png');
    background-repeat: no-repeat;
    background-position: center;
}
.id1 
{
    background:linear-gradient(60deg,rgb(13, 71, 198),white,gold);
    padding: 5px;
    width: 50%;
    border: solid 3px black;
    border-radius: 15px;
    display: flex;
    justify-content: space-evenly;
    flex-direction: row-reverse;
    margin: auto;
}

.head 
{
    color: rgb(8, 6, 6);
    font-weight: bold;
    font-size: 60px;
    width: 40%;
    padding: 8px;
}
.quote 
{
    font-style: italic;
    font-size: 25px;
    color: rgb(60, 4, 47);
}

.info 
{
    font-size: 18px;
    font-weight: bold;
    color: rgb(28, 6, 48);
}

.images 
{
    display: flex;
    justify-content: space-evenly;
    margin-top: 40px;
}

img 
{
    width: 400px;
    height:300px;
    border-radius: 10px;
    border: 2px solid;
}
.content{
    text-align: center;
    padding:10px;
    margin:auto;
}
.footer {
    position: fixed;      
    bottom: 0;          
    left: 0;
    width: 100%;          
    text-align: center;
    padding: 3px;
    font-size: 15px;
    background-color: rgb(194, 195, 115);
    border-top: 2px solid black;
}
.img1
{
    background-image: url('Screenshot 2025-12-25 220130.png');
    background-repeat: no-repeat;
    background-position: center;
}
.id1 
{
    background:linear-gradient(60deg,rgb(36, 28, 100),white,gold);
    padding: 5px;
    width: 50%;
    border: solid 3px black;
    border-radius: 15px;
    display: flex;
    justify-content: space-evenly;
    flex-direction: row-reverse;
    margin: auto;
}
.head 
{
    color: rgb(122, 8, 8);
    font-weight: bold;
    font-size: 60px;
    width: 40%;
    padding: 8px;
}
.footer {
    position: fixed;      
    bottom: 0;          
    left: 0;
    width: 100%;          
    text-align: center;
    padding: 3px;
    font-size: 15px;
    background-color: rgb(182, 201, 95);
    border-top: 2px solid black;
}
.row {
    display: flex;             
    justify-content: space-evenly;                
    gap: 20px;                 
    margin-top: 40px;
}

.admin {
    text-align: center;
    background-color: rgb(135, 165, 239);
    padding: 10px;
    border-radius: 10px;
    border: 2px solid orangered;
    width: 200px;          
}
img {
    width: 180px;
    height: 250px;
    border-radius: 10px;
    border: 2px solid rgb(11, 11, 11);
}
.detail{
    font-size: 16px;
    color: rgb(0, 0, 0);
    font-weight: bold;
    padding: 10px;
}
.high{
    color: orangered;
}

.img1
{
    background-image: url('Screenshot 2025-12-25 220130.png');
    background-repeat: no-repeat;
    background-position: center;
}
.id1 
{
    background:linear-gradient(60deg,rgb(12, 25, 125),white,gold);
    padding: 5px;
    width: 50%;
    border: solid 3px black;
    border-radius: 15px;
    display: flex;
    justify-content: space-evenly;
    flex-direction: row-reverse;
    margin: auto;
}
.head 
{
    color: rgb(208, 24, 24);
    font-weight: bold;
    font-size: 60px;
    width: 40%;
    padding: 8px;
}
.content{

    padding:10px;
    margin:auto;
}
.footer {
    position: fixed;      
    bottom: 0;          
    left: 0;
    width: 100%;          
    text-align: center;
    padding: 3px;
    font-size: 15px;
    background-color: rgb(136, 145, 67);
    border-top: 2px solid black;
}
.info 
{
    font-size: 18px;
    font-weight: bold;
    color: rgb(79, 235, 17);
}
.img1
{
    background-image: url('Screenshot 2025-12-25 220130.png');
    background-repeat: no-repeat;
    background-position: center;
}
.id1 
{
    background:linear-gradient(60deg,rgb(53, 11, 96),white,gold);
    padding: 5px;
    width: 50%;
    border: solid 3px black;
    border-radius: 15px;
    display: flex;
    justify-content: space-evenly;
    flex-direction: row-reverse;
    margin: auto;
}
.head 
{
    color: rgb(243, 8, 83);
    font-weight: bold;
    font-size: 60px;
    width: 40%;
    padding: 8px;
}
.footer {
    position: fixed;      
    bottom: 0;          
    left: 0;
    width: 100%;          
    text-align: center;
    padding: 3px;
    font-size: 15px;
    background-color: rgb(124, 92, 132);
    border-top: 2px solid black;
}
.row {
    display: flex;             
    justify-content: space-evenly;                
    gap: 20px;                 
    margin-top: 40px;
}

.food {
    text-align: center;
    background-color: rgb(179, 161, 237);
    padding: 10px;
    border-radius: 10px;
    border: 2px solid orangered;
    width: 200px;          
}
img {
    width: 180px;
    height: 250px;
    border-radius: 10px;
    border: 2px solid orangered;
}
.detail{
    font-size: 16px;
    color: rgb(0, 0, 0);
    font-weight: bold;
    padding: 10px;
}
.high{
    color: orangered;
}

```

## OUTPUT:
![alt text](<Screenshot 2025-12-27 151814.png>)
![alt text](<Screenshot 2025-12-27 151846.png>)
![alt text](<Screenshot 2025-12-27 151916.png>)
![alt text](<Screenshot 2025-12-27 151951.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
