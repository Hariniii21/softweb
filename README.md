# Ex.07 Software Product Company Website
## Date:

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contact Page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(priya\ softapp.webp);
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .bg-contact {
        border: 1px;
        padding: 10px;
        color: white;
        background-color: peachpuff;
        border-radius: 30px;
      }
      .logo {
        color: pink;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: palevioletred;
      }
      .navbar form {
        width: 300px;
        height: 40px;
        display: flex;
        background: black;
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      .navbar form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: white;
      }
      ::placeholder {
        color: white;
      }
      .navbar form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: bl;
        border-radius: 10px;
        background: aquamarine;
        cursor: pointer;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: bl;
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: rgb(234, 255, 0);
        color: #081b29;
        box-shadow: white;
      }
      .box {
        display: flex;
        column-gap: 40px;
        background: transparent;
        position: relative;
        top: 50px;
        width: 220px;
      }
      .box-1 {
        height: 400px;
        width: 400px;
        border: 3px solid white;
        border-radius: 20px;
        background: transparent;
        position: relative;
        left: 250px;
      }
      .box-2 {
        height: 400px;
        width: 400px;
        border: 3px solid white;
        border-radius: 20px;
        background: transparent;
        position: relative;
        left: 300px;
      }
      .box-1 form {
        display: flex;
        color: antiquewhite;
        background: transparent;
        padding: 10px;
        font-size: 15px;
        position: relative;
        top: 15px;
      }
      .box-1 form input {
        background: transparent;
        display: flex;
        border: 1px solid antiquewhite;
        border-radius: 10px;
        padding: 15px 30px;
        font-size: 15px;
        color: whitesmoke;
        position: relative;
        top: 30px;
      }
      .box-1 form textarea {
        background: transparent;
        color: white;
        padding: 15px 10px;
        position: relative;
        top: 30px;
        left: 20px;
        border: 1px solid white;
        border-radius: 10px;
        width: 300px;
      }
      .box-1 form button {
        border: 0;
        outline: none;
        padding: 10px 20px;
        color: black;
        border-radius: 30px;
        background: white;
        cursor: pointer;
        position: relative;
        top: 50px;
      }
      .box-2 h2 {
        color: white;
        position: relative;
        top: 25px;
        left: 50px;
        font-size: 30px;
      }
      .box-2 p {
        color: white;
        position: relative;
        top: 50px;
        padding: 10px 80px;
      }
      .box-2 span {
        color: rgb(212, 255, 0);
        font-size: 20px;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: paleturquoise;
        color: #081b29;
        box-shadow: 0 0 20px rgb(242, 255, 0);
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">DI<span>GITAL</span>DR<span>EAMERS</span></h1>
        <ul>
          <li><a href="home.html"> Home </a></li>
          <li><a href="product.html"> Product </a></li>
          <li><a href="people.html"> people </a></li>
          <li><a href="contact.html" class="bg-contact"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="box">
        <div class="box-1">
          <form>
            <center>
              <h1>Contact Us</h1>
              <input type="text" placeholder="Your Name" />
              <br />
              <input type="email" placeholder="Your Email" />
              <br />
              
              <br />
              <button type="submit">Submit</button>
            </center>
          </form>
        </div>
        <div class="box-2">
          <h2>Contact Information</h2>
          <p>
            <span>Address</span> :No7/4,south street,M.reddiapatti
          </p>
          <p><span>Email</span> : harinisuburam@gmail.com</p>
          <p><span>Phone</span> : 9962483158</p>
        </div>
      </div>
    </div>
    <footer>
      <center>DESIGNED AND DEVELOPED BY Harini (212223240048)</center>
    </footer>
  </body>
</html>
```

## OUTPUT:
![Screenshot 2024-05-09 134521](https://github.com/Hariniii21/softweb/assets/147140423/79a1cbeb-b044-46bf-96bd-e327bacb1b80)
![Screenshot 2024-05-09 135803](https://github.com/Hariniii21/softweb/assets/147140423/c7354b89-d57e-41bc-adf4-c28acd1548a1)
![Screenshot 2024-05-09 135659](https://github.com/Hariniii21/softweb/assets/147140423/5e6a73d7-7163-423d-890b-be510b78cdfa)
![Screenshot 2024-05-09 134325](https://github.com/Hariniii21/softweb/assets/147140423/08426b75-3416-44ca-bf35-5a7a6ca69117)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
