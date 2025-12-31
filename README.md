<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">

<title>ABAKWA TV NETWORK</title>

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
  padding:15px 20px;
  background:rgba(0,0,0,0.85);
  flex-wrap:wrap;
}

.logo{
  display:flex;
  align-items:center;
  gap:10px;
}

.logo-icon{
  width:32px;
  height:32px;
  border-radius:50%;
  background:linear-gradient(135deg,var(--gold),#c98a00);
}

.logo strong{color:var(--gold);}
.logo small{
  display:block;
  font-size:10px;
  opacity:.7;
}

nav{
  width:100%;
  margin-top:10px;
  display:flex;
  justify-content:space-between;
  overflow-x:auto;
}

nav a{
  color:#ccc;
  text-decoration:none;
  font-size:14px;
  white-space:nowrap;
}
nav a.active{color:var(--gold);}

/* HERO */
.hero{
  min-height:65vh;
  background:
    linear-gradient(to right,rgba(0,0,0,.9),rgba(0,0,0,.2)),
    url("https://images.unsplash.com/photo-1524985069026-dd778a71c7b4?auto=format&fit=crop&w=1600&q=80");
  background-size:cover;
  background-position:center;
  padding:40px 20px;
}

.live{
  background:var(--red);
  padding:6px 12px;
  font-weight:bold;
  display:inline-block;
}

.hero h1{
  font-size:34px;
  margin-top:15px;
}
.hero h1 span{color:var(--gold);}

.hero p{
  margin-top:10px;
  font-size:15px;
}

.watch{
  margin-top:20px;
  padding:12px 28px;
  font-size:15px;
  border:none;
  background:linear-gradient(135deg,#e00,#900);
  color:#fff;
  border-radius:6px;
  cursor:pointer;
}

/* CONTENT */
.content{
  padding:25px 20px;
}

.content h2{
  margin:25px 0 12px;
  font-size:18px;
}

.row{
  display:flex;
  gap:15px;
  overflow-x:auto;
  padding-bottom:10px;
}

.card{
  min-width:200px;
  height:120px;
  background:var(--card);
  border-radius:14px;
  display:flex;
  align-items:flex-end;
  padding:14px;
  font-size:14px;
  font-weight:600;
}

/* CHANNELS */
.channels{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:15px;
  padding:25px 20px;
}

.channel{
  background:linear-gradient(135deg,var(--gold),#c98a00);
  padding:12px;
  border-radius:10px;
  font-weight:bold;
  text-align:center;
  color:#000;
  font-size:14px;
}

/* FOOTER */
footer{
  text-align:center;
  padding:18px;
  font-size:13px;
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
    <a>Live</a>
    <a>Movies</a>
    <a>Series</a>
    <a>News</a>
  </nav>
</header>

<section class="hero">
  <span class="live">LIVE NOW</span>
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
</footer>

</body>
</html>
