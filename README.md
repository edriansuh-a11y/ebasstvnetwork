
<html lang="en">
<head>
<meta charset="UTF-8">
<title>ABAKWA <a href="http://ebasstvnetworkapp"><img src="" alt=""></a>TV NETWORK</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
:root{
  --gold:#f5c16c;
  --dark:#060606;
  --red:#b11212;
  --card:linear-gradient(135deg,#3a1c0f,#000);
}

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:"Segoe UI",Arial,sans-serif;
}

body{
  background:radial-gradient(circle at top,#1a0f0a,#000);
  color:#fff;
}

/* NAVBAR */
.navbar{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:18px 50px;
  background:rgba(0,0,0,0.85);
}

.logo{
  display:flex;
  align-items:center;
  gap:12px;
}

.logo-icon{
  width:34px;
  height:34px;
  border-radius:50%;
  background:linear-gradient(135deg,var(--gold),#c98a00);
}

.logo strong{color:var(--gold);}
.logo small{display:block;font-size:10px;opacity:.7}

nav a{
  margin-left:25px;
  color:#ccc;
  text-decoration:none;
  cursor:pointer;
}
nav a.active{color:var(--gold);}

/* HERO */
.hero{
  height:78vh;
  background:
    linear-gradient(to right,rgba(0,0,0,.9),rgba(0,0,0,.2)),
    url("https://images.unsplash.com/photo-1524985069026-dd778a71c7b4?auto=format&fit=crop&w=1600&q=80");
  background-size:cover;
  background-position:center;
  padding:80px;
}

.live{
  background:var(--red);
  padding:6px 14px;
  font-weight:bold;
}

.hero h1{
  font-size:56px;
  margin-top:20px;
}
.hero h1 span{color:var(--gold);}

.hero p{
  margin-top:12px;
  font-size:18px;
}

.watch{
  margin-top:25px;
  padding:15px 34px;
  font-size:16px;
  border:none;
  background:linear-gradient(135deg,#e00,#900);
  color:#fff;
  border-radius:6px;
  cursor:pointer;
}

/* CONTENT */
.content{padding:40px 50px;}
.content h2{margin:30px 0 15px;}

.row{
  display:flex;
  gap:20px;
  overflow-x:auto;
}

.card{
  min-width:240px;
  height:135px;
  background:var(--card);
  border-radius:14px;
  display:flex;
  align-items:flex-end;
  padding:16px;
  font-weight:600;
  transition:.3s;
}
.card:hover{transform:scale(1.08);}

/* CHANNELS */
.channels{
  display:flex;
  justify-content:center;
  gap:25px;
  padding:35px;
}

.channel{
  background:linear-gradient(135deg,var(--gold),#c98a00);
  padding:14px 30px;
  border-radius:10px;
  font-weight:bold;
  color:#000;
}

/* FOOTER */
footer{
  text-align:center;
  padding:20px;
  font-size:14px;
  opacity:.7;
}
</style>
</head>

<body>

<header class="navbar">
  <div class="logo">
    <div class="logo-icon"></div>
    <div>
      <strong>EBASS</strong> TV NETWORK
      <small>Powered by EBASS GROUP</small>
    </div>
  </div>

  <nav>
    <a class="active">Home</a>
    <a>Live TV</a>
    <a>Movies</a>
    <a>Series</a>
    <a>News</a>
  </nav>
</header>

<section class="hero">
  <span class="live">LIVE NOW:</span>
  <h1>Entertainment <span>Tonight</span></h1>
  <p>Celebrity News & Gossip – Watch Now!</p>
  <button class="watch">▶ WATCH LIVE</button>
</section>

<section class="content">
  <h2>Continue Watching</h2>
  <div class="row">
    <div class="card">Kingdom of Power</div>
    <div class="card">African Beats</div>
    <div class="card">Urban Comedy</div>
    <div class="card">Tribal Quest</div>
  </div>

  <h2>Trending Now</h2>
  <div class="row">
    <div class="card">AfroStars Music Show</div>
    <div class="card">The Heist</div>
    <div class="card">Royal Destiny</div>
    <div class="card">Lagos Nights</div>
  </div>

  <h2>EBASS Originals ⭐</h2>
  <div class="row">
    <div class="card">City Hustle</div>
    <div class="card">Desert Warriors</div>
    <div class="card">Game Changer</div>
    <div class="card">Heart of Africa</div>
  </div>
</section>

<section class="channels">
  <div class="channel">EBASS LIVE</div>
  <div class="channel">NEWS 24/7</div>
  <div class="channel">MOVIES ZONE</div>
  <div class="channel">SPORTS HD</div>
</section>

<footer>
  © 2025 EBASS GROUP — All Rights Reserved

</head>

<body>

</body>

</html>
