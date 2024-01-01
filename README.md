# Ex04 Places Around Me
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
## map.html
```
<html>
	<head>
		<title> My City </title>
	</head>
	<body bgcolor="aliceblue">
		<h1 align="center">
		<font color="teal"><b> KAMARAJPURAM </b></font>
		</h1>
		<h3 align="center">
		<font color="LightSeaGreen"><b> SREEKUMAR S (212223240157) </b></font>
		</h3>
		<center>
		<img src="/static/map.png" usemap="#MyCity" height="605" width="1450">
		<map name="MyCity">
			<area shape="circle" coords="725,340,100" href="temple.html" title="ALAVATTAMMAN KOVIL PARK">
            <area shape="circle" coords="1210,425,50" href="siva.html" title="SIVA TEMPLE">
            <area shape="circle" coords="1000,210,100" href="mercy.html" title="MERCY ELECTRONICS">
            <area shape="circle" coords="550,150,100" href="cake.html" title="CAKE SQUARE">
            <area shape="circle" coords="1400,425,70" href="prince.html" title="PRINCE">
		</map>
		</center>
	</body>
</html>


```
## cake.html
```
<html>
	<head>
		<title>My City</title>
	</head>
	<body bgcolor="lemonchiffon">
		<h1 align="center">
		<font color="brown" ><b>KAMARAJAPURAM</b></font>
		</h1>
		<h2 align="center">
		<font color="maroon"><b>CAKE SQUARE</b></font>
		</h2>
		<hr size="4" color="red" >
			<p align="center" >
				<font face="calibria" size="4" >
					Cake Square! The American Pastry Hub First time in Chennai The most spectacular cake shop in Chennai, chiefly specialized in offering scrumptious bakery products and desserts in fabulous flavors and tastes at unbeatable price ranges. You can find an eclectic range of best tasting cake varieties to choose from. Our cakes chiefly stand for superior quality, unparalleled design ranges and lip-smacking taste that never fails to titillate your taste buds!<br><br>

					Furthermore adding on, we boast ourselves as the one among the very few cake shops in Chennai, who own a boutique for designing 15 layered designer cakes that chiefly accomplish to be a stunning showpiece for various extravagant wedding bashes. The chief specialty of preparing these designer cakes is that, the design pattern or theme which we implement on this cake will never be repeated for next three years, since the design pattern we use for every 15 layered wedding cake is extremely unique and incomparable from other designer cakes in the city.<br><br>
					
					The brand Cake Square belongs to the company S R CAKE PRIVATE LIMITED.<br>			</font>
			</p>
	</body>
</html>

```
## siva.html
```
<html>
	<head>
		<title>My City</title>
	</head>
	<body bgcolor="lemonchiffon">
		<h1 align="center">
		<font color="brown" ><b>KAMARAJAPURAM</b></font>
		</h1>
		<h2 align="center">
		<font color="maroon"><b>SIVA TEMPLE</b></font>
		</h2>
		<hr size="4" color="red" >
			<p align="center" >
				<font face="calibria" size="4" >
					One of the rarest temple where God and Goddess are together. It's very good looking. Temple has almost all God. There is a separate shannathi for Saraswathi.<br><br>
                    Privately managed temple. Clean and neat. Priests are polite and respected the Devotees. Nice place to worship. They perform Yagam on special occasions . Main God is Chandramoulesswarar. Apart from you have Vinayagar, Subramanyar, Saraswathi, Bhuvaneswari , Mahavishnu, Ayyappan, Bhairavar, Annapoorani and Durga has seperate sannidhi. Navagraha also there .</font>
			</p>
	</body>
</html>
```
## mercy.html
```
<html>
	<head>
		<title>My City</title>
	</head>
	<body bgcolor="lemonchiffon">
		<h1 align="center">
		<font color="brown" ><b>KAMARAJAPURAM</b></font>
		</h1>
		<h2 align="center">
		<font color="maroon"><b>Mercy Electronics</b></font>
		</h2>
		<hr size="4" color="red" >
			<p align="center" >
				<font face="calibria" size="4" >What began as a simple brick and mortar electricals shop served its customers well for years, but Mr. Edward Kennedy was quick to notice the shifting trend of a growing Electronics market.That was when he took a leap of faith to convert his Electricals shop to an Electronics store and his journey began with Mercy Electronics as an emerging brand.<br><br>

					Mercy Electronics has been a household name for over three decades now and it has grown to become much more than just a store, it is now a thriving 15-store chain spread across Chennai with plans of expanding across Tamil Nadu and then hopefully throughout India as well.<br></font>
			</p>
	</body>
</html>
```
## prince.html
```
<html>
	<head>
		<title>My City</title>
	</head>
	<body bgcolor="lemonchiffon">
		<h1 align="center">
		<font color="brown" ><b>KAMARAJAPURAM</b></font>
		</h1>
		<h2 align="center">
		<font color="maroon"><b>Prince Shri Venkateshwara Arts and Science College</b></font>
		</h2>
		<hr size="4" color="red" >
			<p align="center" >
				<font face="calibria" size="4" >
					The Prince Educational Society was established in the year 1978 by our Founder & Chairman Dr. K. Vasudevan, M.A., B.Ed., Ph.d. He cherishes his dream vision by imparting knowledge in today's youth to be responsible citizens of tomorrow. Over the years, the society has seen tremendous growth in the education sector</font>
			</p>
	</body>
</html>
```
## temple.html
```
<html>
	<head>
		<title>My City</title>
	</head>
	<body bgcolor="lemonchiffon">
		<h1 align="center">
		<font color="brown" ><b>KAMARAJAPURAM</b></font>
		</h1>
		<h2 align="center">
		<font color="maroon"><b>Alavattamman Kovil Park</b></font>
		</h2>
		<hr size="4" color="red" >
			<p align="center" >
				<font face="calibria" size="4" >
					Alavattamman Kovil Park is located at Alavattamman Temple Rd, Sembakkam, Chennai, Tamil Nadu 600073, India.<br><br>
					Alavattamman Kovil Park is 7 days open between 04:45 AM to 10:15 AM.<br><br>
					Alavattamman Kovil Park is nearly 4.19 kilometers away from Chennai International Airport Metro Station. You can go to this metro station by using the Metro MRT Blue Line.<br><br>
				</p>
	</body>
</html>
```


## OUTPUT
![Screenshot 2024-01-01 143754](https://github.com/guru14789/NearMe/assets/151705853/95538d96-2d71-4859-ac33-33462281ce96)

![Screenshot 2024-01-01 143852](https://github.com/guru14789/NearMe/assets/151705853/9f4b81bb-04e3-468f-994f-f3356fa93d46)
008-92d0b59f9091)
![Screenshot 2024-01-01 143817](https://github.com/guru14789/NearMe/assets/151705853/6afa463f-25c1-48aa-aa05-cb95d28ae529)
![Screenshot 2024-01-01 143929](https://github.com/guru14789/NearMe/assets/151705853/5c5d4b1d-9081-4ef6-b05e-996d12a13e56)
![Screenshot 2024-01-01 143912](https://github.com/guru14789/NearMe/assets/151705853/619f80e6-eb1d-4bc2-848d-ff079ca59bd7)
![Screenshot 2024-01-01 143737](https://github.com/guru14789/NearMe/assets/151705853/14f3d4d5-9c93-4b83-b251-c5b9bc37968a)








## RESULT
The program for implementing image maps using HTML is executed successfully.
