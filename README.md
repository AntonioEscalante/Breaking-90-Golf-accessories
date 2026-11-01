<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Elite Golf Accessories</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#f4f4f4;
}

/* HEADER */

header{
    background:#0a5c2f;
    color:white;
    padding:20px;
}

.navbar{
    display:flex;
    justify-content:space-between;
    align-items:center;
    flex-wrap:wrap;
}

.logo{
    font-size:28px;
    font-weight:bold;
}

.nav-links a{
    color:white;
    text-decoration:none;
    margin-left:20px;
    font-weight:bold;
}

/* HERO */

.hero{
    background:linear-gradient(
        rgba(0,0,0,.5),
        rgba(0,0,0,.5)
    ),
    url('https://images.unsplash.com/photo-1535131749006-b7f58c99034b?w=1600');
    background-size:cover;
    background-position:center;
    height:500px;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
}

.hero-content{
    color:white;
}

.hero-content h1{
    font-size:3rem;
}

.hero-content p{
    margin-top:15px;
    font-size:18px;
}

.shop-btn{
    display:inline-block;
    margin-top:20px;
    padding:12px 30px;
    background:#ffd700;
    color:black;
    text-decoration:none;
    border-radius:5px;
    font-weight:bold;
}

/* PRODUCTS */

.products{
    padding:50px 8%;
}

.section-title{
    text-align:center;
    margin-bottom:40px;
    color:#0a5c2f;
}

.product-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.product-card{
    background:white;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 3px 10px rgba(0,0,0,.15);
    transition:.3s;
}

.product-card:hover{
    transform:translateY(-5px);
}

.product-card img{
    width:100%;
    height:230px;
    object-fit:cover;
}

.product-info{
    padding:15px;
}

.product-info h3{
    margin-bottom:10px;
}

.price{
    color:#0a5c2f;
    font-size:20px;
    font-weight:bold;
    margin:10px 0;
}

.buy-btn{
    width:100%;
    padding:12px;
    border:none;
    background:#0a5c2f;
    color:white;
    font-weight:bold;
    border-radius:5px;
    cursor:pointer;
}

.buy-btn:hover{
    background:#084521;
}

/* CART */

.cart-section{
    width:90%;
    max-width:800px;
    margin:40px auto;
    background:white;
    padding:25px;
    border-radius:10px;
    box-shadow:0 5px 10px rgba(0,0,0,.15);
}

.cart-section h2{
    color:#0a5c2f;
    margin-bottom:20px;
}

.cart-item{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:10px;
    border-bottom:1px solid #ddd;
}

.remove-btn{
    background:red;
    color:white;
    border:none;
    padding:6px 10px;
    cursor:pointer;
    border-radius:4px;
}

.checkout-btn{
    margin-top:20px;
    background:#ffd700;
    border:none;
    padding:12px 20px;
    font-size:16px;
    font-weight:bold;
    border-radius:5px;
    cursor:pointer;
}

.checkout-btn:hover{
    background:#e8c400;
}

/* FOOTER */

footer{
    margin-top:50px;
    background:#222;
    color:white;
    text-align:center;
    padding:25px;
}

.footer-btn{
    display:inline-block
