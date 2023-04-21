# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

### Step 1:
Clone the github repository into Theia IDE.
### Step 2:
Create a new Django project.
### Step 3:
Write the needed HTML code.
### Step 4:
Run the Django server and execute the HTML files.
## Code:
```
map.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Vellore - leather hub</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>AsinVardhini (212222100007)</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/ghs.html" title="Golden Temple">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/rto.html" title="VIT">
<area shape="circle" coords="400,350,50" href="/static/html/vk.html" title="Christian Medical College & Hospital">
<area shape="circle" coords="400,200,75" href="/static/html/bus.html" title="Hi-Tech Bus Stand">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/park.html" title="Vellore-Fort">
</map>
</center>
</body>
</html>

temple.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Golden Temple</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Vellore - leather hub</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Golden Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
The Sripuram Golden Temple is a sight to behold, and it is situated
in Tirumalaikodi at Southern Vellore, Tamil Nadu. The golden temple 
sits inside a spiritual park or ‘Spiritual Oasis’, and a star path
 leads the visitors towards it.The main feature of the temple has 
 to be that it is covered in real gold foil and it is regarded as 
 the biggest and the only temple to do that. 
</b>
</font>
</p>
</body>
</html>

vit.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>VIT</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Vellore - leather hub</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>VIT</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
<b>
It was established under Section 3 of the University Grants Commission (UGC) Act,
1956, and was founded in 1984 as a self-financing institution called the Vellore Engineering College. 
The Union Ministry of Human Resources Development conferred University status on
 Vellore Engineering College in 2001.
</b>
</font>
</p>
</body>
</html>

college.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>CMC</title>
</head>
<body bgcolor="lime">
<h1 align="center">
<font color="red"><b>Vellore - leather hub</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Christian Medical College & Hospital</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
<b>
CMC Vellore has brought many significant achievements to India, including 
starting the first College of Nursing in 1946, performing the first 
reconstructive surgery for leprosy in the world (1948), performing the 
first successful open heart surgery in India (1961), performing the first 
kidney transplant in India (1971), performing first bone marrow 
transplantation (1986) in India and performing thefirst successful ABO 
incompatible kidney transplant in India (2009).
</b>
</font>
</p>
</body>
</html>

fort.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Fort</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Vellore - leather hub</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Vellore-Fort</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
Vellore Fort is a large 16th-century fort situated in heart of the Vellore
city, in the state of Tamil Nadu, India built by Vijayanagara kings. 
The fort was at one time the headquarters of the Aravidu Dynasty of the
Vijayanagara Empire. The fort is known for its grand ramparts, wide moat and robust masonry.
</font>
</p>
</body>
</html>

bus.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Bus Stand</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>Vellore - leather hub</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Hi-Tech Bus Stand</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>
Vellor is a city and the administrative headquarters of Vellore district in
the Indian state of Tamil Nadu.It is located on the banks of the Palar River
in the northeastern part of Tamil Nadu and is separated into four zones that 
are further subdivided into 60 wards, covering an area of 87.915 km2 and 
housing a population of 423,425 as reported by the 2001 census. It is located 
about 137.20 kilometres (85 mi) west of Chennai, and about 213.20 kilometres 
(132 mi) east of Bangalore.Vellore is located on the Mumbai–Chennai arm of the 
Golden Quadrilateral. 
</b>
</font>
</p>
</body>
</html>

```
## Output:
![map](https://user-images.githubusercontent.com/119417735/233532108-a3db69f7-c07b-4848-92dd-0a25ea14a20e.png)

![temple](https://user-images.githubusercontent.com/119417735/233532346-e7cda7a0-4b80-4896-8811-68df5034211d.png)

![vit](https://user-images.githubusercontent.com/119417735/233532496-bccc0194-9e78-4947-b55f-63f12c055b90.png)

![cmc](https://user-images.githubusercontent.com/119417735/233532665-d5bacf11-aed5-4741-a197-d663919bedf3.png)

![bus](https://user-images.githubusercontent.com/119417735/233532861-bfc12704-5850-49d8-a4a5-a6d1dbd5ec2f.png)

![fort](https://user-images.githubusercontent.com/119417735/233532979-fe9310a7-c6f7-4d5b-88bd-a3f07f0f8b89.png)

![2023-04-21 (6)](https://user-images.githubusercontent.com/119417735/233533084-9a38af54-0e58-4a86-91cc-0b63d7eef25f.png)

## Result:
Thus A website to display details about the places in map is successfully executed and displayed.
