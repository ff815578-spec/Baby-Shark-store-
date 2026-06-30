# Baby-Shark-store-<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Baby Shark Store</title>

<style>
body{
margin:0;
font-family:Arial,sans-serif;
background:#f5f5f5;
}
header{
background:#000;
color:#fff;
text-align:center;
padding:20px;
}
.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
gap:15px;
padding:20px;
}
.card{
background:#fff;
border-radius:10px;
padding:10px;
box-shadow:0 0 10px rgba(0,0,0,.1);
text-align:center;
}
.card img{
width:100%;
border-radius:10px;
}
button{
background:#000;
color:#fff;
border:none;
padding:10px 20px;
border-radius:5px;
cursor:pointer;
}
</style>
</head>

<body>

<header>
<h1>Baby Shark Store</h1>
<p>Premium T-Shirts Collection</p>
</header>

<div class="products">
