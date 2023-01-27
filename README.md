# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

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

### Step 6:

Publish the website in the given URL.

## PROGRAM :
## CSS CODE:
```html
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("/static/img/cricket_team.webp");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #d11616;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #5bb045;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
    background-image: url("/static/img/cricket\ background.jpg");
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
    font-weight: 900;
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
    color: rgb(203, 19, 19);
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #5bb045;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #9c1018;
}
```
## Home Page:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>cricket</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Indian Cricket Team</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/building.png" alt="Building" />
          <div class="contenttext">
            Cricket was introduced to the Indian subcontinent by British sailors in the 18th century, and the first cricket club was established in 1792. India's national cricket team played its first international match on 25 June 1932 in a Lord's Test, becoming the sixth team to be granted Test cricket status.
            <br />
            As per the latest Odi rankings released by ICC on 24 Jan 2023, India with 114 rating is placed at the top of the points table. England with 113 rating is on the second spot. Australia with 112 rating occupies the third place.
            <ul>
              <li>Winning Cricket World Cup in 1983.</li>
              <li>INDIA won the ICC World T20 in 2007.</li>
              <li>INDIA achieved Number-One in ICC Test ranking in 2009</li>
              <li>INDIA won the 2011 Cricket World Cup.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 cricket acdemy, Developed by Gumma Dileep Kumar.
      </div>
    </div>
  </body>
</html>
```
## PRODUCT CODE:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Cricket</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Indian Cricket Team.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our requiredments</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/cricketbat.jpg" alt="product image">
                  </div>
                  <div class="itemname">bat</div>
                  <div class="itemprice">Price: Rs.10,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/cricketkit.jpg"  alt="product image">
                  </div>
                  <div class="itemname">kit</div>
                  <div class="itemprice">Price: Rs.50,000.00 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 cricket academy, Developed by Gumma Dileep Kumar.
      </div>
    </div>
  </body>
</html>
```


## 

## OUTPUT:
### Home Page:
![Screenshot (64)](https://user-images.githubusercontent.com/118707761/215133809-d4ba673f-71e0-49e6-9470-755d8d0f48bd.png)
### Product Page:
![Screenshot (65)](https://user-images.githubusercontent.com/118707761/215134047-db5c9222-d6e5-4952-9428-5811219fccbf.png)
### Validator:


![Screenshot (66)](https://user-images.githubusercontent.com/118707761/215135743-33bd4b67-d5c9-481d-815d-403b2f8cc555.png)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
