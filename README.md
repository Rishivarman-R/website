# Ex.07 Restaurant Website
# Date:19.12.2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurants Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #50030b;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            background-color: #b9e948;
            color: rgb(106, 96, 9);
            padding: 10px 0;
        }
        nav a {
            color: rgb(115, 66, 212);
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #d31111;
            color: rgb(239, 243, 246);
        }
        .content {
            padding: 20px;
        }
        .restaurant {
            margin-bottom: 20px;
            border: 1px solid #a00c0c;
            padding: 10px;
        }
        footer {
            background-color: #3c0606;
            color: rgb(236, 241, 241);
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    
        body{
          background-image:url(oldpp.jpg);
          background-repeat: no-repeat;
          background-position:center;
          background-attachment: fixed;
          background-size:cover;
        }
    </style>
</head>
<body>

<header>
    <h1>🎭DIGBYS RESTAURANT🪽</h1>
    <a href="file:///C:/Users/admin/Desktop/TIMETABLE/formfill.html" style="color: white;">THEVS</a>
</header>

<nav>
    <a href="#indian">🥘Indian</a>
    <a href="#chinese">🍜Chinese</a>
    <a href="#sea food">🦞Sea food</a>
    <a href="#tamilnadu specials">☕tamilnadu specials</a>
    
</nav>
<div class="content">
    <section id="indian">
        <h2>🥘Indian Restaurants</h2>
        <div class="restaurant">
            <img src="india.jpeg" height="200px" width="200px">
            <h3>briyani</h3>
            <p>Enjoy authentic Indian dishes and a cozy atmosphere.</p>
        </div>
        <div class="restaurant">
            <img src="Chapati 2.webp"  height="200px" width="200px" alt="carbone image">
            <h3>sambar</h3>
            <p>Experience classic Indian dining in a vibrant setting.</p>
        </div>
    </section>

    <section id="chinese">
        <h2>🍜Chinese Restaurants</h2>
        <div class="restaurant">
<img src="SpicyMisoRamen_Square.jpg" width="200px" height="200px">
            <h3>roman</h3>
            <p>Fast-casual dining featuring Chinese-American cuisine.</p>
        </div>
        <div class="restaurant">
            <img src="noodles.jpeg" alt="hakkasan image">
            <h3>noodels</h3>
            <p>Elegant dining with a modern twist on traditional Chinese dishes.</p>
        </div>
    </section>

    <section id="sea food">
        <h2>🦞sea food Restaurants</h2>
        <div class="restaurant">
            <img src="sea food.jpeg" height="200px" width="200px">
            <h3>prawn</h3>
            <p>Build your own burritos, bowls, and tacos with fresh ingredients.</p>
        </div>
        <div class="restaurant">
            <img src="fishlink.jpeg" height="200px" width="200px"  alt="fiber image">
            <h3>fish</h3>
            <p>Enjoy a variety of traditional sea food dishes in a festive atmosphere.</p>
        </div>
    </section>
    <section id="Tamilnadu specials">
        <h2>☕tamilnadu Restaurants</h2>
        <div class="restaurant">
            <img src="tamilnadu.jpeg" height="200px" width="200px">  
            <h3>dosa</h3>
            <p>Enjoy authentic Tamilnadu specials dishes and a cozy atmosphere.</p>
        </div>
        <div class="restaurant">
            <img src="idly.jpeg" height="200px" width="200px"  alt="fiber image">
            <h3>idly</h3>
            <p>Experience classic Indian dining in a vibrant setting.</p>
        </div>
    </section>
</div>

<footer>
    <p>&copy; 2024 Restaurants Guide. All rights reserved.</p>
</footer>

</body>
</html>
```
```


<html>
    <form>
        <body>
            <style>
                body{
                    background-image:url(RESTAURANT.jpg);
                    background-image: url(RESTAURANT form.jpg);
                    background-repeat: no-repeat;
                    background-position:center;
                    background-attachment: fixed;
                    background-size:cover;
                }
                .title{
                    font-size: 60px;
            font-weight:bolder;
            color: #b00d0d;
            font-family: "calibran", normal;
            font-style: italic;
    }
 
                
               </style>
            <header>
               
                <center>
                <nav>
                <div class="title">🎭DIGBYS RESTAURANT🪽</div>
                <div class="footer"></div>
            </nav>
            </center>
            </header>
    <center>
        <title>
             RESTAURANT
        </title>
        <body  style="background-image: SpicyMisoRamen_Square.jpg;">
            <header>
                <title> <h1>🎭DIGBYS RESTAURANT🪽</h1></title>
            </header>
        <table border="5" style=width: aria-controls="33"">
            
    <tr> 
        <td>Name:</td>
        <td><input type="text" placeholder="enter your name"></td>
    </tr>
    <tr>
         <td>Address:</td>
         <td> <input type="text" placeholder="enter your adderss"></td>
    </tr>
    <tr>
        <td>Mobile number:</td>
        <td><input type="number" placeholder="enter your Mobile number"></td>
    </tr>
   
     <tr>
        <td>Food Preferences:</td>
        <td>
            <select> 
                <option>
                    <h1>INDIAN FOODS</h1>
                </option>
                <OPTION>curry</OPTION>
                <option>Tikka</option>
                <option>rajma chawal</option>
                <OPTION>ras malai</OPTION>
                <option>hyderabadi biriyani</option>
                <option>Chakna</option>
                <option>Sev</option>
                <option>Roti</option>
                <option>bhey</option>
                <option>Avial</option>
                <option>Vadapav</option>
                <option>ven pongal</option>
                <option>malabar biriyani</option>
                <option>food meals</option><hr>
                <option>
                    <h1>CHINESE FOODS</h1>
                </option>
                <option>peking duck </option>
                <option>dumplings</option>
                <option>Roman</option>
                <option>Noodeles</option>
                <option>Dim sum</option>
                <option>char siu</option>
                <option>Ma po tofu</option>
                <option>chow mein </option><hr>
                <option>
                    <h1>SEA FOOD</h1>
                </option>
                <option>Abalone</option>
                <option>sea urchin</option>
                <option>catfish</option>
                <option>Crab</option>
                <option>Tilapia</option>
                <option>Lobster</option>
                <option>Squid</option>
                <option>salmon</option>
                <option>Shrimp</option>
                <option>Caviar</option>
                <option>Sardines</option>
                <option>mussels</option>
                <option>Tuna</option>
                <option>
                    <h1>TAMILNADU specials</h1>
                </option>
                <option>Dosa</option>
                <option>Idli</option>
                <option>Sambar</option>
                <option>pongal</option>
                <option>Lemon rice</option>
                <option>chicken Chettinad</option>
                <option>uttapam</option>
                <option>kuzhi paniyaram</option>
                <option>Rasam</option>
                <option>Vadai</option>

            </select>
        </td>
        <tr>
            <td><button>
                 <a hr"https://www.bing.com/search?pglt=2083&q=DIGBYS+RESTAURANT&cvid=8426d8b95b804551bc393ff998cbcae4&gs_lcrp=EgRlZGdlKgYIABBFGDkyBggAEEUYOTIGCAEQABhAMgYIAhAAGEAyBggDEAAYQDIGCAQQABhAMgYIBRAAGEAyBggGEAAYQDIGCAcQABhA0gEIMTA1OWowajGoAgCwAgA&FORM=ANNTA1&PC=LCTS"></a>order now</button></td>
            <td><button>order cancle</button></td>

        </tr>
       
       </table>
       <hr>
       
    </center>
</body>
    </form>
</html>
```
# OUTPUT:
![Screenshot (58)](https://github.com/user-attachments/assets/e7031848-ce15-498c-8ade-4438118446e2)

![Screenshot (59)](https://github.com/user-attachments/assets/1eceffc3-6ec6-4aca-adba-a249232659c6)

![Screenshot (60)](https://github.com/user-attachments/assets/c755ec44-4589-466a-96f2-f20e647b390f)

![Screenshot (61)](https://github.com/user-attachments/assets/e1186d70-e786-4d34-ab13-266b73c576e4)

![Screenshot (63)](https://github.com/user-attachments/assets/853b1748-8abc-44d2-8b74-a1c06199d677)



# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
