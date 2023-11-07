Main.html
<html>
<head>
    <title>Main Page</title>
    <style type="text/css">
        a
        {
            color:Black;
            font-size:large;    
        }
    </style>
</head>
<body style="background-image: url(BgImg2.jpg); background-repeat: no-repeat; background-size: 100%;">
    <center>
        <h1 style="color:White;">
            Main Page</h1>
        <br />
        <p>
            <b><a href="Home.html">Home</a></b>
        </p>
        <p>
            <b><a href="SignUp.html">Register</a></b>
        </p>
        <p>
            <b><a href="Order.html">Order</a></b>
        </p>
    </center>
</body>
</html>

Home.html
<html>
<head>
    <title>Home</title>
</head>
<body  style="background-image: url(cbgimg1.jpg); background-repeat: no-repeat; background-size: 100%; color:White;">
<center>
    <h1>Welcome to e-Books</h1> 
</center>
  <p>Select your book</p>
    <hr />
<center>
<p>
<a href="CheckOut.html"><img src="BgImg1.jpg"  height="250" width="250" /></a>
<a href="CheckOut.html"><img src="BgImg1.jpg"  height="250" width="250" /></a>
<a href="CheckOut.html"><img src="BgImg1.jpg"  height="250" width="250" /></a>
<a href="CheckOut.html"><img src="BgImg1.jpg"  height="250" width="250" /></a>
<a href="CheckOut.html"><img src="BgImg1.jpg"  height="250" width="250" /></a>
</p>
</center>
<center><a href="MainPage.html">Go to Main page</a></center>
</body>
</html>

Checkout.html
<html>
<head>
    <title>Checkout</title>
</head>
<body style="background-image: url(cbgimg1.jpg); background-repeat: no-repeat; background-size: 100%; color:White;">
    <center><h1>Checkout</h1></center>
    <p>Enter Card details</p>
    <hr />
    Card No : <input type="text" /> <br /><br />
    Name on Card : <input type="text" /> <br /><br />
    Expiry date : <select >
        <option>2018</option>
        <option>2019</option>
        <option>2020</option>
        <option>2021</option>
    </select> <br /><br />
    CVV No : <input type="text" /> <br /><br />
    Amount paid : <input type="text" /> <br /><br />
    <input type="submit" value="Submit" /><input type="reset" value="reset" /> <br />
    <center>
    <a href="MainPage.html">Go to Main Page</a>
    </center>
</body>
</html>

Order.html
<html>
<head>
    <title>Order</title>
</head>
<body  style="background-image: url(cbgimg1.jpg); background-repeat: no-repeat; background-size: 100%; color:White;">
    <center>
        <h1>
            Order</h1>
    <hr />
        <p>
            Your Order</p>
        <a href="MainPage.html">Go to Main Page</a></center>
</body>
</html>

Signup.html
<html>
<head>
    <title>Sign up</title>
</head>
<body style="background-image: url(cbgimg1.jpg); background-repeat: no-repeat; background-size: 100%; color:White;">
<center><h1>Sign up</h1></center>
    <p>Enter your details</p>
    <hr />
    First Name : <input type="text" /> <br /><br />
    Last Name : <input type="text" /> <br /><br />
    Email Id   : <input type="text" /> <br /><br />
    User Id : <input type="text" /> <br /><br />
    Password : <input type="password" /> <br /><br />
    Phone No : <input type="text" /> <br /><br />
    Day : <input type="text" /> <br /><br />
    <input type="submit" value="Submit" /><input type="reset" value="reset" /> <br />
    <center>
    <a href="MainPage.html">Go to Main Page</a>
    </center>
</body>
</html>

