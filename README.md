# Ex.06 Restaurant Website
## Date:

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
home.html
```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> LITTLE ITALIAN RESTRUANT HOME</title>
  <link rel="stylesheet" href="home.css">
</head>
<body>
  <header>
    <h1>LITTLE ITALIAN RESTAURENT</h1>
    
    <nav>
      <ul>
        <li><a href="index.html" class="active">HOME</a></li>
        <li><a href="menu.html">MENU</a></li>
        <li><a href="admin.html">ADMIN</a></li>
        <li><a href="contact.html">CONTACT</a></li>
      </ul>
    </nav>
  </header>

  <section class="home">
    <h2></color>WELCOME TO OUR RESTAURENT</h2>
    <p>LITTLE ITALIAN RESTRUANT is a modern restaurant that blends creative flavors with the warmth of live-fire cooking. It offers a cozy ambiance and delicious dishes crafted with passion and style.</p>
    <img src="ITALI.png">
  </section>

  <footer>
    <p>LITTLE ITALIAN RESTRUANT  ©  <strong>  SAKTHIVEL B- 25004373</strong></p>
  </footer>
</body>
</html>
```
home.css
```


body {
  background-image:url('back.webp');
  font-family: Arial, sans-serif;
  background-color: rgb(245, 241, 239);
  color: rgb(249, 243, 243);
  margin: 0;
  text-align: center;
}

header {
  background-color:  #0d0d0d;
  padding: 20px;
  border-bottom: 0px solid rgb(30, 210, 241);
}

h1 {
    position:relative;
  color: rgb(10, 210, 245);
  right:30%;
  top:20%;
}
nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: rgb(194, 94, 94);
  text-decoration: none;
  font-weight: bold;
  position: relative;
  left:30%;
  
}

nav a.active,
nav a:hover {
  color: rgb(10, 210, 245);

  position: relative;
  left:30%;
}


.home {
  padding: 40px;
}

.home img {
  width: 500px;
  border-radius: 20px;
  margin-top: 20px;
  border: 3px solid rgb(10, 210, 245);

}

footer {
  background-color: black;
  color: #deb4b4;
  padding: 10px;
  border-top: 2px solid red;
}
```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LITTLE ITALIAN RESTAURENT MENUS</title>
  <link rel="stylesheet" href="menu.css">
</head>
<body>
  <header>
    <h1>LIST OF FOOD</h1>
    <nav>
      <ul>
        <li><a href="home.html">HOME</a></li>
        <li><a href="menu.html" class="active">MENU</a></li>
        <li><a href="admin.html">ADMIN</a></li>
        <li><a href="contact.html">CONTACT</a></li>
      </ul>
    </nav>
  </header>

  <section class="menu">
    <h2>Food Items</h2>
    <div class="menu-items">
      <div class="item"><img src="alfredo.jpg"><p>alfredo - Rs.550</p></div>
      <div class="item"><img src="aranchini.jpeg"><p>aranchini : Rs.700</p></div>
      <div class="item"><img src="lasangna.webp"><p>lasangna: Rs.600</p></div>
      <div class="item"><img src="pasta.jpg"><p>pasat: Rs.250</p></div>
      <div class="item"><img src="pizza margherita.jpg"><p>pizza margherita : Rs.750</p></div>
      <div class="item"><img src="prawn spaghetti.jpg"><p>prawn spaghetti: Rs.850</p></div>
      <div class="item"><img src="salad.webp"><p> salad : Rs.240</p></div>
      <div class="item"><img src="tiramisu.webp"><p>tiramisu: Rs.600</p></div>
    </div>
  </section>

  <footer>
    <p>LITTLE ITALIAN RESTAURENT 2025 ©  <strong>SAKTHIVEL B - 25004373</strong></p>
  </footer>
</body>
</html>
```
menu.css
```
body {
  font-family: Arial, sans-serif;
  background-color: #111;
  color: white;
  margin: 0;
  text-align: center;
}

header {
  background-color: black;
  padding: 50px;
  border-bottom: 3px solid rgb(244, 5, 5);
}

h1 {
  color:rgb(244, 5, 5);

  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 1px;
}

nav ul li {
  display: inline;
  margin: 15px;
}

nav a {
  color: rgb(247, 231, 231);
  text-decoration: none;
  font-weight: bold;
}

nav a.active,
nav a:hover {
  color:rgb(231, 5, 5);

}

.menu {
  padding: 10px;
}

.menu-items {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 10px;
}

.item {
  background-color: black;
  border: 2px solid rgb(5, 224, 244);
  border-radius: 30px;
  padding: 10px;
  width: 100px;
}

.item img {
  width: 100%;
  border-radius: 6px;
}

footer {
  background-color: black;
  font-size: large;
  color:rgb(16, 181, 164);
  padding: 10px;
  border-top: 2px solid red;
}
```
admin.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LITTLE ITALIAN RESTAURENT ADMINS</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
    <header>
        <h1>ADMINS OF RESTAURANT</h1>
        <nav>
            <ul>
                <li><a href="home.html">HOME</a></li>
                <li><a href="menu.html">MENU</a></li>
                <li><a href="admin.html" class="active">ADMIN</a></li>
                <li><a href="contact.html">CONTACT</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h2>LITTLE ITALIAN !! TEAM LCU</h2>

        <div class="team">
            <div class="member">
                <img src="WhatsApp Image 2025-12-26 at 2.13.44 PM.jpeg"alt="SAKTHIVEL">
                <h3>SAKTHIVEL</h3>
                <p>FOUNDER & CEO</p>
            </div>

            <div class="member">
                <img src="surya.jpg" alt="SURYA">
                <h3>ROLEX</h3>
                <p>EXCECUTIVE CHEF</p>
            </div>

            <div class="member">
                <img src= "vijay.webp"alt="VIJAY">
                <h3>LEO</h3>
                <p>RESTRURANT MANAGER</p>
            </div>

            <div class="member">
                <img src="kamal.webp" alt="KAMAL">
                <h3>VIKRAM</h3>
                <p>MARKETING HEAD</p>
            </div>

            <div class="member">
                <img src= "vijay sethupadi.jpg"alt="SANTHANAM">
                <h3>SANTHANAM</h3>
                <p>HR & STAFF MANAGER</p>
            </div>

            <div class="member">
                <img src= "karthi.webp"alt="KARTHI">
                <h3>DILLI</h3>
                <p>CUSTOMER SERVICE MANAGER</p>
            </div>
            </div>
        </div>
    </main>

    <footer>
        <p>LITTLE ITALIAN RESTAURENT 2025 ©    <strong>SAKTHIVEL B - 25004373</strong></p>
    </footer>
</body>
</html>
```
admin.css
```
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background-color: #f00303;
}

/* Header */
header {
    background-color: #0a0a0a;
    color: rgb(10, 216, 248);
    text-align: center;
    padding: 20px 0;
}

header h1 {
    margin: 0;
    font-size: 2em;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 10px 0 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: rgb(227, 233, 231);
    font-weight: 600;
}

nav ul li a.active {
    text-decoration: underline;
}

/* Main Section */
main {
    text-align: center;
    padding: 40px 20px;
}

main h2 {
    color: #222;
    font-size: 1.8em;
    margin-bottom: 40px;
}

/* Team Cards */
.team {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.member {
    background-color: #111;
    color: rgb(199, 68, 68);
    border-radius: 12px;
    width: 150px;
    padding: 10px;
    transition: transform 0.3s;
}

.member:hover {
    transform: translateY(-8px);
}

.member img {
    width: 90%;
    height: 210px;
    object-fit: cover;
    border: 4px solid rgb(255, 41, 3);
}

.member h3 {
    margin-top: 15px;
    color: #fff;
    font-size: 1.2em;
}

.member p {
    color: #d6a206;
    font-weight: 500;
}

/* Footer */
footer {
    background-color: #442727;
    color: white;
    text-align: center;
    padding: 8px;
    font-size: 0.9em;
}
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CONTACT ** LITTLE ITALIAN</title>
  <link rel="stylesheet" href="contact.css">
</head>
<body>
  <header>
    <h1>CONTACT DETAILS</h1>
    <nav>
      <ul>
        <li><a href="home.html">HOME</a></li>
        <li><a href="menu.html">MENU</a></li>
        <li><a href="admin.html">ADMIN</a></li>
        <li><a href="contact.html" class="active">     CONTACT </a></li>
      </ul>
    </nav>
  </header>

  <section class="contact">
    <h2>CONTACT DETAILS</h2>
    <p> Address: 3, Ground Floor, 10, Wallace Garden 3rd Street, Thousand Lights West, Nungambakkam, Chennai, Tamil Nadu 600006, India </p>
    <p> PH NO : 0001100111</p>
    <p> lokeshcinimaticuniverse@gmail.com</p>
  </section>

  <footer>
    <p>LITTLE ITALIAN RESTAURENT 2025 © <strong>SAKTHIVEL B - 25004373</strong></p>
  </footer>
</body>
</html>
```
contact.css
```


body {
  font-family: Arial, sans-serif;
  background-color: rgb(223, 234, 234);
  color: rgb(24, 5, 5);
  margin: 0;
  text-align: center;
  overflow: hidden;
}

header {
  background-color: rgb(16, 15, 15);
  padding: 20px;
  border-bottom: 3px solid rgb(143, 206, 227);
}

h1 {
  color: white;
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 8px;
}

nav ul li {
  display: inline;
  margin:  15px;
}

nav a {
  color: rgb(13, 240, 237);
  text-decoration: none;
  font-weight: bold;
}

nav a.active,
nav a:hover {
  color: rgb(204, 240, 228);
}

.contact {
  padding: 45px;
  object-fit: cover;
  border: 70px solid rgb(240, 67, 67);
}

footer {
  position:relative;
  font-size: large;
  background-color:  #ec4646;
  color: #f3ebeb;
  top:50px;
  padding: 20px;

}
```

## OUTPUT:
![alt text](<Screenshot 2025-12-26 210850.png>)

![alt text](<Screenshot 2025-12-26 210906.png>)

![alt text](<Screenshot 2025-12-26 210926.png>)

![alt text](<Screenshot 2025-12-26 210941.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
