# Amazon-Practice
Amazon Practice HTML &amp; CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon Style Navigation</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header class="navbar">
    <a href="#" class="nav-logo border">
        <img src="https://pngimg.com/uploads/amazon/amazon_PNG11.png" alt="Amazon Logo">
    </a>
    <div class="nav-adress border">
        <p class="add-first">Deliver to</p>
        <div class="add-icon">
<i class="fa-solid fa-location-dot"></i>
            <p class="add-second">Bangladesh</p>
        </div>
    </div>
<div class="nav-search">
    <select class="search-select">
        <option>All</option>
    </select>
    <input placeholder="Search Amazon" class="search-input">
    <div class="search-icon">
        <i class="fa-solid fa-magnifying-glass"></i>
    </div>
</div>
<div class="nav-signin  border">
    <p><span>Hello, Sign in</span></p>
    <p class="nav-second">Account & List</p>
</div>
<div class="nav-return border">
    <p><span>Returns</span></p>
    <p class="nav-second">& Orders</p>
</div>
<div class="nav-cart">
    <i class="fa-solid fa-cart-shopping"></i> Cart
</div>

</header>

</body>
</html>


* {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    border: border-box;
}

.navbar {
    height: 70px;
    background-color: #0f1111;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-evenly;

}

.nav-logo {
    height: 40px;
    width: 105px;
    margin: 1px;
    padding: 1px 8px 0px 6px;
    background-size: cover;
    display: flex;
    padding-top: 10px;
}

.border {
    border: 2px solid transparent;
}

.border:hover {
    border: 1.5px solid white;
}
.add-first {
    color: #CCCCCC;
    font-size: 0.70rem;
    margin-left: 18px;
}
.add-second {
    color: #CCCCCC;
    font-size: 1rem;
    margin-left: 3px;
}

.add-icon {
    display: flex;
    align-items: center;
    margin-left: 3px;
}
.nav-search {
    display: flex;
    justify-content: space-evenly;
    background-color: pink;
    width: 620px;
    height: 40px;
    border-radius: 4px;
}

.search-select {
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    border: none;
}
.search-input {
    width: 100%;
    font-size: 1rem;
    border: none;
}

.search-icon {
    width: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.5rem;
    background-color: #febd68;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
    color: #0f1111;
}
.nav-search:hover {
    border: 2px solid orange;
}
span {
    font-size: 0.7rem;
}
.nav-second {
    font-size: 0.85rem;
    font-weight: 700;
}
.nav-cart i {
font-size: 30px;
}

.nav-cart {
    font-size: 0.85rem;
    font-weight: 700;
}

