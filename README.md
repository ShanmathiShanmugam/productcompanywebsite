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

## OUTPUT:
### sample.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AAVIN PRIVATE LIMITED</title>
    <link rel="stylesheet" href= "./css/layout.css" />
    <link rel="icon" href="/static/img/logo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>AAVIN PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/img/logo.png" alt="Building" />
          <div class="contenttext">
            Aavin Pvt Ltd is the exclusive dealer for milk and milk products across Tamil Nadu and runs world class (Retail and wholesale) facilities across the state. Trusted by many proud owners and adding more to the aavin family, Aavin pvt ltd continues to remain committed in setting high benchmark in quality and taste in the food sector across Tamil Nadu in Chennai, Ambattur, Coimbatore and in Puducherry.

            Aavin Pvt Ltd team works with one motto – providing you products with taste and no.1 quality.

            The company produces a wide range of products, including milk, butter, yogurt, ice cream, ghee, milk shake, khoa, tea, coffee, and chocolate, among other goods.

            You know you have come to the right place when you reach a AAVIN facility. Feel free to walk into any of our shops across Tamil Nadu or call us. It would be our pleasure to welcome you to any of our offices at your convenience. We look forward to share the sheer pleasure experience of a tasty aavin product with you.
            <br />
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 AAVIN PRIVATE LIMITED DEVELOPED BY S.SHANMATHI.
      </div>
    </div>
  </body>
</html>

```
### product.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Aavin Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/img/logo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>AAVIN PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/product.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1><b>OUR PREMIUM PRODUCTS</b></h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/green.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Aavin Milk-Green</div>
                  <div class="itemprice">Price: Rs:22 </div>
              </div>
          <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/blue.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">Aavin Milk-Blue</div>
                  <div class="itemprice">Price: Rs:20 </div>
              </div>
          <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/orange.jpeg" alt="product image">
                  </div>
                  <div class="itemname">Aavin Milk-Orange</div>
                  <div class="itemprice">Price: Rs:25</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/pink.jpeg" alt="product image">
                </div>
                <div class="itemname">Aavin Milk-Pink</div>
                <div class="itemprice">Price: Rs:18</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/brown.jpeg" alt="product image">
                </div>
                <div class="itemname">Aavin Milk-Brown</div>
                <div class="itemprice">Price: Rs:30</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/ghee.jpeg" alt="product image">
                </div>
                <div class="itemname">Aavin Ghee-1ltr-jar</div>
                <div class="itemprice">Price: Rs:460</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/curd.jpeg" alt="product image">
                </div>
                <div class="itemname">Aavin Curd-100ml</div>
                <div class="itemprice">Price: Rs:25</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/butter.jpeg" alt="product image">
                </div>
                <div class="itemname">Aavin Butter-500g</div>
                <div class="itemprice">Price: Rs:250</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/chocolate.jpeg" alt="product image">
                </div>
                <div class="itemname">Aavin Chocolate</div>
                <div class="itemprice">Price: Rs:45</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/palkova.jpeg" alt="product image">
                </div>
                <div class="itemname">Aavin palkova-100g</div>
                <div class="itemprice">Price: Rs:50</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/paneer.png" alt="product image">
                </div>
                <div class="itemname">Aavin Paneer-250g</div>
                <div class="itemprice">Price: Rs:150</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/kulfi.jpeg" alt="product image">
                </div>
                <div class="itemname">Aavin kulfi</div>
                <div class="itemprice">Price: Rs:45</div>
            </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 Aavin PRIVATE LIMITED DEVELOPED BY S.Shanmathi.
      </div>
    </div>
  </body>
</html>
```
### people.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AAVIN PRIVATE LIMITED</title>
    <link rel="stylesheet" href="./css/contact.css" />
    <link rel="icon" href="/static/img/logo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>AAVIN PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <body>
          <div class="content">
              <h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Our Proud Management Crew!!!</h2>
              <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/n.png" height="400" width="400"></align><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                    Nethraa Jeyachandran (Chairman)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/k.jpg" height="400" width="400"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                    Kothai Kumar (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/r.jpg" height="400" width="400"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                     Ragul (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/p.jpg" height="400" width="400"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                    Prithviraj(Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/m.png" height="400" width="400"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Mithra mukundaa (Deputy Manager)</h2></centre>
      </div>
      <div class="footer">
        Copyright &#169; 2023 AAVIN PRIVATE LIMITED DEVELOPED BY S.SHANMATHI.
      </div>
    </div>
  </body>
</html>
```

### contact.html
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>AAVIN </title>
    <link rel="stylesheet" href="./css/contact.css" />
    <link rel="icon" href="/static/img/logo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>AAVIN PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <body>
          <div class="content">
            <h1>&emsp;Contact Us</h1>
                    <p><b>&emsp;Here are the details listed below. Do contact us for any need</b></p>
                    <b><h2>&emsp;Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                         No:6A,Thirumangalaam main road,Chennai,Tamilnadu,India.
                    </p>
                    <ul>
                        <li><b>&emsp;Phone</b>:&emsp;9934567789</li>
                        <li><b>&emsp;Shop owner no</b>:&emsp;9586456745</li>
                        <li><b>&emsp;Shop Manager Number:</b>7010586334</li>
                        <li><b>&emsp;Email Id:</b>&emsp;aavinprivatelimited1@gmail.com</li>
                        <li><b>&emsp;Email Id:</b>&emsp;naavinprivatelimited2@gmail.com</li>
                    </ul>
          </div>
          </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 AAVIN PRIVATE LIMITED DEVELOPED BY S.SHANMATHI.
      </div>
    </div>
  </body>
</html>
```

### layout.css
```
*{
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
  
  body {
    background-color:#260a65e5;
    color:#000000;
    background-image: url("/static/img/background2.jpg");
    background-repeat: no-repeat;
    background-size: cover;
  }
  .container {
    width: 1080px;
    margin-left: auto;
    margin-right: auto;
    border-width: 1px 1px 1px 1px;
    border-style: solid;
    box-shadow: 15px 15px 8px white;
  }
  
  .banner {
    display: block;
    width: 100%;
    height: 250px;
    text-align: center;
    font-size: 60px;
    font-family: inherit;
    background-color: #09d7ee;
    background-size: 100% 100%;
    margin: -100px 0px 0px 0px;
    padding-top: 150px;
    color: #000000;
  }
  
  .menu {
    display: block;
    width: 100%;
    height: 50px;
    font-size: larger;
    background-color:  #09d7ee;
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
    color:  #09d7ee;
  }
  
  .menuitem a {
    text-decoration: none;
    color: darkblue;
  }
  
  .content {

    display: block;
    width: 100%;
    background-color:rgb(255,255,255);
    min-height: 500px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
    border-color: #09d7ee;
    border-style: solid;
  }
  .homecontent {
    min-height: 500px;
    margin: 10px 10px 10px 10px;
  }
  .homecontent h1 {
    text-align: left;
  }
  .homecontent img {
    float: right;
    width: 400px;
    height: 300px;
    margin-left: 10px;
  }
  
  .contenttext {
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
    background-color: #09d7ee;
    text-align: center;
    padding-top: 10px;
    margin: 0px 0px 0px 0px;
    color: #1b044ce5;
 }
```
### contact.css
```
* {
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
  body {
    background-color: #260a65e5;
    color: #000000;
    background-image: url("/static/img/background2.jpg");
    background-repeat: no-repeat;
    background-size: cover;
  }
  .container {
    width: 1080px;
    margin-left: auto;
    margin-right: auto;
    border-width: 1px 1px 1px 1px;
    border-style: solid;
    box-shadow: 15px 15px 8px white;
  }
  
  .banner {
    display: block;
    width: 100%;
    height: 250px;
    text-align: center;
    font-size: 60px;
    font-family: inherit;
    background-color: aqua;
    background-size: 100% 100%;
    margin: -100px 0px 0px 0px;
    padding-top: 150px;
    color: #e7e7e7;
  }
  
  .menu {
    display: block;
    width: 100%;
    height: 50px;
    font-size: larger;
    background-color: #09d7ee;
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
    color: #09d7ee;
  }
  
  .menuitem a {
    text-decoration: none;
    color: darkblue;
  }
  
  .content {
    display: block;
    width: 100%;
    background-color: #ffffff;
    font-size: 20px;
    min-height: 500px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
    border-color:#09d7ee;
    border-style: solid;
  }
  .homecontent {
    min-height: 500px;
    margin: 10px 10px 10px 10px;
  }
  .homecontent h1 {
    text-align: left;
  }
  .homecontent img {
    float: right;
    width: 400px;
    height: 300px;
    margin-left: 10px;
  }
  
  .contenttext {
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
    background-color:#09d7ee;
    text-align: center;
    padding-top: 10px;
    margin: 0px 0px 0px 0px;
    color: #260a65e5;
  }
```

### Home Page:
![hp](https://github.com/ShanmathiShanmugam/productcompanywebsite/assets/121243595/27e10986-ade2-4955-a7f9-88068bb5ab0b)

### Product page: 
![prod1](https://github.com/ShanmathiShanmugam/productcompanywebsite/assets/121243595/4259c6d9-ae15-4c94-8be6-eea84119f922)

![prod2](https://github.com/ShanmathiShanmugam/productcompanywebsite/assets/121243595/f65182cc-0bee-4998-8818-1aea92443be5)

### People page:
![ppl1](https://github.com/ShanmathiShanmugam/productcompanywebsite/assets/121243595/752ad2b3-2d84-4ebb-8b78-3573c62d9c96)

![ppl2](https://github.com/ShanmathiShanmugam/productcompanywebsite/assets/121243595/d530a9cc-8d16-4f16-8f09-c014d846df91)

![ppl3](https://github.com/ShanmathiShanmugam/productcompanywebsite/assets/121243595/c85b88f5-fd74-47cc-95ab-74ee19ab41dc)

### Contact us page:
![contact](https://github.com/ShanmathiShanmugam/productcompanywebsite/assets/121243595/b4c340de-b763-4f78-98dd-6e349d90adf7)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
