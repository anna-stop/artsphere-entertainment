# artsphere-entertainment
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ArtSphere Entertainment</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f5f5f5;
color:#333;
line-height:1.6;
}

header{
background:linear-gradient(135deg,#111827,#374151);
color:white;
padding:80px 20px;
text-align:center;
}

header h1{
font-size:48px;
margin-bottom:10px;
}

header p{
font-size:20px;
opacity:.9;
}

.container{
max-width:1200px;
margin:auto;
padding:60px 20px;
}

.section-title{
text-align:center;
font-size:36px;
margin-bottom:40px;
color:#111827;
}

.card{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 4px 15px rgba(0,0,0,.1);
margin-bottom:30px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.service{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 4px 12px rgba(0,0,0,.08);
transition:.3s;
}

.service:hover{
transform:translateY(-5px);
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:220px;
object-fit:cover;
border-radius:
