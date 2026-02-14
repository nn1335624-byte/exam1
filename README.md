<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Coffeeroasters</title>
  <link rel="stylesheet" href="./index.css" />
  <link href="https://fonts.googleapis.com/css2?family=Fraunces:wght@400;700&display=swap"  
  rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>

<body>
  <header class="navbar">
    <div class="logo">
      <img src="c:\Users\noura\Downloads\Logo.png">
    </div>

    <nav>
      <a href="#">HOME</a>
      <a href="#">ABOUT US</a>
      <a href="#">CREATE YOUR PLAN</a>
    </nav>
  </header>
  <section class="photo">     
    <div class="hero">    
      <h1>Great coffee<br>made simple.</h1>

      <p>
        Start your mornings with the world’s best coffees.
        Try our.<br> expertly curated artisan coffees from our
        best roasters<br> delivered directly to your door, at
        your schedule.
      </p>

      <button>Create your plan</button>
    </div>
  </section>
  <section class="headline">
    <h1>Our Collection</h1>
    <div class="Images">
      <div class="text">
    <img src="WhatsApp Image 2026-01-18 at 1.20.53 PM.jpeg">
    <h3>Gran Espresso</h3>
    <p>Light and flavorful blend with cocoa <br>and black pepper for an intense <br>experience.</p>
    </div>
    <div class="text">
    <img src="WhatsApp Image 2026-01-18 at 1.22.18 PM.jpeg">
    <h3>Planalto</h3>
   <p>Brazilian dark roast with rich and<br> velvety body, and hints of fruits and<br> nuts.</p>
    </div>
    <div class="text">
    <img src="WhatsApp Image 2026-01-18 at 1.22.46 PM.jpeg">
    <h3>Piccollo</h3>
    <p>Mild and smooth blend featuring <br>notes of toasted almond and dried <br>cherry.</p>
    </div>
    <div class="text">
    <img src="WhatsApp Image 2026-01-18 at 1.23.11 PM.jpeg">
    <h3>Danche</h3>
    <p>Ethiopian hand-harvested blend<br> densely packed with vibrant fruit<br> notes.</p>
    </div>
    </div>
     </section>

      <section class="boxs">
        <div class="card">
          <h1>Why choose us?</h1>
          <p>A large part of our role is choosing which particular coffees will be featured <br>
           in our range. This means working closely with the best coffee growers to give<br>
           you a more impactful experience on every level.</p>
  <di class="cards">
 <div class="logos">
          <img src="WhatsApp Image 2026-01-18 at 3.13.31 PM.jpeg">
          <h4>Best quality</h4>
          <p>Discover an endless variety of the world’s<br> best artisan coffee from each of our<br>  roasters.</p>
        </div>
        <div class="logos">
          <img src="WhatsApp Image 2026-01-18 at 3.13.46 PM.jpeg">
          <h4>Exclusive benefits</h4>
          <p>Special offers and swag when you <br>subscribe, including 30% off your first <br>shipment.</p>
        </div>
        <div class="logos">
          <img src="WhatsApp Image 2026-01-18 at 3.13.59 PM.jpeg">
          <h4>Free shipping</h4>
          <p>We cover the cost and coffee is delivered  <br>fast. Peak freshness: guaranteed.</p>
        </div>
        </div>
        </div>
          </section>
          <section class="numbers">
            <div class="footer">
              <header class="header_footer">
                <h3>How it works</h3>
              </header>

              <div class="container">
         <div class="circle"></div>
         <div class="line"></div>
         <div class="circle"></div>
         <div class="line"></div>
         <div class="circle"></div>
</div>

            </div>
          </section>
          <section class="number">
          <div class="numbers">
    <span>01</span>
    <span>02</span>
    <span>03</span>
  </div>
          </section>
          <section class="footer_text">
            <div>
              <h2>Pick your<br> coffee</h2>
    <p>Select from our evolving range of artisan<br> coffees. Our beans are ethically sourced<br> and we pay fair prices for them. There are<br> new coffees in all profiles every month <br>for you to try out.</p>
       <button>Create your plan</button>
            </div>
            <div>
              <h2>Choose the <br>frequency</h2>
    <p>Customize your order frequency,<br> quantity, even your roast style and grind <br>type. Pause, skip or cancel your<br> subscription with no commitment<br> through our online portal.</p>
            </div>
            <div>
               <h2>Receive and <br>enjoy!</h2>
    <p>We ship your package within 48 hours,<br> freshly roasted. Sit back and enjoy<br> award-winning world-class coffees<br> curated to provide a distinct tasting<br> experience.</p>
            </div>

          </section>
        <header class="header3">
          <div class="logo3">
      <img src="Footer Logo.png">
    </div>
  <nav>
      <a href="#">HOME</a>
      <a href="#">ABOUT US</a>
      <a href="#">CREATE YOUR PLAN</a>
    </nav>

    <div class="social-icons">
  <a href="" target="_blank"><i class="fab fa-facebook-f"></i></a>
  <a href="" target="_blank"><i class="fab fa-instagram"></i></a>
  <a href="" target="_blank"><i class="fab fa-twitter"></i></a>
</div>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 25px 80px;
}

.logo img {
  width: 150px;
}

nav a {
  text-decoration: none;
  margin-left: 30px;
  color: #83888f;
  font-weight: bold;
  font-size: 14px;
}

nav a:hover {
  color: #333;
}

.photo {
  margin: 0 80px;
  min-height: 600px;
  background-image: url("860c8df123844131ed36b3306e3664755d89e7b2 (4).png");
  background-size: cover;
  background-position: center;
  border-radius: 10px;
  padding: 100px;
  color: white;
}

.hero {
  max-width: 500px;
}

.hero h1 {
  font-size: 56px;
  line-height: 1.1;
  margin-bottom: 25px;
}

.hero p {
  font-size: 16px;
  line-height: 1.6;
  margin-bottom: 30px;
  color: #fefcf7;
}

.hero button {
  background-color: #0e8784;
  color: white;
  border: none;
  padding: 15px 35px;
  border-radius: 6px;
  font-size: 16px;
  cursor: pointer;
}

.hero button:hover {
  background-color: #66d2cf;
}

.headline{
  padding: 150px;
}

.headline h1{
  font-family: "playfair display",serif;
  font-size: 170px;
  font-weight: 700;
  text-transform: lowercase;
  background: linear-gradient(180deg, rgba(254, 252, 247, 0.0001) 0%, #FEFCF7 100%);
  -webkit-text-fill-color: transparent;
  background-clip: text;
 -webkit-background-clip: text;
  color: transparent;
  letter-spacing: 2px;
  background-color: #696969;
  text-align: center;
}


.headline h3{
  font-family: Fraunces;
font-weight: 900;
font-style: Black;
font-size: 24px;
line-height: 150%;
letter-spacing: 0px;
text-align: center;

}

.headline p{
font-family: 'Barlow', sans-serif;
font-weight: 400;
font-size: 16px;
line-height: 160%;
letter-spacing: 0px;
text-align: center;
color: var(--colors-neutral-900, rgba(51, 61, 75, 1));

}


body{
  background-color:  #f8f8f8;
}


.Images{
  background-color: #f8f8f8;
  display: flex;
  gap: 40px;
  justify-content: space-between;
  align-items: flex-end;
  position: relative;
  z-index: 3;

}


.text h3{
  font-family: "playfair display",serif;
  font-size: 30px;
  font-weight: 900;
}

.text p{
 font-family: "playfair display",serif;
 font-size: 15px;
 color: #444343;
 margin-top: 30px;

}

.boxs{
    align-items: center;
  justify-content: center;
  display: flex;
}

.card{
  width: 80%;
  height: 75vh;
  background-color:rgba(51, 61, 75, 1) ;
  padding: 100px;
  text-align: center;
  justify-content: center;
}

.card h1{
  color:rgba(254, 252, 247, 1);
  font-family: "playfair display",serif;
  font-size: 50px;

}

.card p{
  color: rgba(131, 136, 143, 1);
  margin-top: 30px;
}

.cards {
  display: flex;
  justify-content: space-between;
  gap: 30px;
  margin-top: 80px;
}

.logos {
  background:rgba(14, 135, 132, 1);
  padding: 40px 25px;
  border-radius: 10px;
  flex: 1;

}

.logos img{
  width: 60px;
  margin-bottom: 30px;
}

.logos h4{
   font-size: 22px;
  margin-bottom: 15px;
  color: rgba(254, 252, 247, 1);
}

.logos p{
  font-size: 15px;
  line-height: 1.6;
  color: rgba(254, 252, 247, 1);
}

.header_footer{
  padding: 100px;
  color: rgba(131, 136, 143, 1);
  font-family:  "playfair display",serif;
  font-size: 25px;
  margin-left: 100px;
}

.container {
  display: flex;
  align-items: center;
  margin-left: 200px;
  margin-top: 0;
 
}

.circle {
  width: 40px;
  height: 30px;
  border-radius: 50%;
  border: 2px solid rgba(14, 135, 132, 1);
    background-color: rgba(254, 252, 247, 1);
}

.line {
  width: 300px;
  height: 3px;
  background-color: rgba(253, 214, 186, 1);
}

.number{
  justify-content: center;
  align-items: center;
  display: flex; 
}

.numbers {
  display: flex;
  gap: 430px;
  margin-top: 100px;
  align-items: center;
}

.numbers span {
  font-size: 72px;
  font-weight: 900;
  font-family: 'Fraunces', serif;
  color: rgba(253, 214, 186, 1);
}

.footer_text{
  display: flex;
  text-align: center;
  justify-content: center;
  gap: 200px;
  margin-top: 30px;
}

.footer_text h2{
  font-weight: 900;
  font-size: 32px;
  font-family: 'Fraunces', serif;
  color: rgba(51, 61, 75, 1);
}

.footer_text p{
  font-size:16px ;
  font-weight: 400;
  color:rgba(51, 61, 75, 1) ;
  font-family: 'Barlow', sans-serif;
  margin-top: 30px;
}

.footer_text button {
  background-color: #0e8784;
  color: white;
  border: none;
  padding: 15px 35px;
  border-radius: 6px;
  font-size: 16px;
  cursor: pointer;
  margin-top: 70px;
}

.footer_text button:hover {
  background-color: #66d2cf;
}

.logo3{
  width: 150px;
 
}

.header3{
  height: 15vh;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 25px 80px;
  margin-top: 200px;
 background-color: rgba(51, 61, 75, 1);

}

.social-icons{
width:80px;
height: 20px;
display: flex;
gap: 20px;
color: #f8f8f8;
}
















*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

body{
  font-family: 'Fraunces', serif;
  line-height:1.6;
}

@media (min-width:768px) and (max-width:1024px){
.navbar{
 padding:30px 60px;
}

.navbar nav a{
  margin-left:30px;
  text-decoration:none;
  font-size:14px;
  font-weight:700;
  width: 283;
  height: 16;
  gap: 40px;
  opacity: 1;
  color: var(--colors-neutral-500, rgba(131, 136, 143, 1));
}

.navbar nav a:hover{
  color:#2c343e;
}

.photo{
padding:60px 40px;
background-position: center;
width: 80%;
height: 504;
gap: spacing/0;
opacity: 1;
padding-top: spacing/1200;
padding-right: spacing/600;
padding-bottom: spacing/1200;
padding-left: spacing/600;
border-radius: corner-radius/10;
}

.hero{
width: 704;
height: 504;
padding-top: spacing/1200;
padding-right: spacing/600;
padding-bottom: spacing/1200;
padding-left: spacing/600;
gap: spacing/0;
opacity: 1;
border-radius: corner-radius/10;
width: 420;
height: 312;
gap: 48;
opacity: 1;
margin-top: 170px;

}

.hero h1{
font-size:42px;
margin-bottom:20px;
font-family: Fraunces;
font-weight: 900;
font-style: Black;
font-size: 48px;
line-height: 100%;
}

.hero p{
font-size:15px;
color:#dcdcdc;
max-width:500px;
margin-bottom:30px;
font-family: Barlow;
font-weight: 400;
font-style: Regular;
font-size: 16px;
line-height: 160%;
letter-spacing: 0px;

}

.hero button{
color:white;
border:none;
font-weight:700;
cursor:pointer;
width: 218;
height: 57;
gap: 12;
opacity: 1;
padding-top: spacing/200;
padding-right: spacing/400;
padding-bottom: spacing/200;
padding-left: spacing/400;
border-radius: corner-radius/6;
background: var(--colors-teal-600, rgba(14, 135, 132, 1));
margin-top: 25px;

}

.headline {
  max-width: 1100px;
  margin: 0 auto;
 
}

.headline h1 {
  font-size: 80px;
  text-align: center;
  margin-bottom: 80px;
  white-space: nowrap;
}


.headline h3{
font-family:'Fraunces', serif;
font-weight: 900;
font-style: Black;
font-size: 24px;
margin: 0;
text-align: right;
font-family: Fraunces;
font-weight: 900;
line-height: 150%;
letter-spacing: 0px;
}
 
.headline p{
font-family: Barlow;
font-weight: 400;
font-style: Regular;
font-size: 16px;
line-height: 160%;
letter-spacing: 0px;
color: var(--colors-neutral-900, rgba(51, 61, 75, 1));
white-space: nowrap;
}
.text img {
  width: 150px;
}

.info {
  max-width: 400px;
}
.Images {
  display: flex;
  flex-direction: column; 
  gap: 80px;
}

.text{
  display: flex;
  align-items: center;
  gap: 80px;
}

.text h3{
  font-size:22px;
  margin-bottom:10px;
}

.text p{
  font-size:14px;
  color:#83888f;
}

  .boxs {
    padding: 40px 30px;
  }

  .card h1 {
    font-size: 32px;
    text-align: center;
  }

  .card > p {
    font-size: 16px;
    line-height: 1.6;
    text-align: center;
    margin-bottom: 40px;
  }

  .cards {
    display: flex;
    flex-direction: column;
    gap: 24px;
  }

  .logos {
    display: flex;
    align-items: center;
    gap: 20px;
    padding: 24px;
    border-radius: 16px;
  }

  .logos img {
    width: 60px;
    height: auto;
  }

  .logos h4 {
    font-size: 20px;
    margin-bottom: 8px;
  }

  .logos p {
    font-size: 15px;
    line-height: 1.5;
  }


.logos img{
  height:60px;
  margin-bottom:20px;
}

.logos h4{
  margin-bottom:10px;
  font-size:18px;
}

.header_footer{
  padding:70px 60px 20px;
  margin-top: 30px;
}

.header_footer h3{
  font-size:28px;
  margin-top: 350px;
  margin-right: 150px;
  

}

 .container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    max-width: 600px;
    margin: 0 auto 40px;
    margin-left: 70px;
    margin-top: 100px;
  }

 .circle {
    width: 24px;
    height: 24px;
    border-radius: 50%;
  }

  .line {
    flex: 1;
    height: 2px;
    margin: 0 10px;
    width: 130px;
  }
.number .numbers{
  display:flex;
  justify-content:space-around;
  font-size:60px;
  color:#fdd6ba;
  font-weight:700;
  padding:40px 0;
  gap: 140px;
    max-width: 600px;
    margin: 0 auto 40px;
    margin-top: 30px;
}

.footer_text{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:40px;
  padding:40px 60px 100px;
}

.footer_text h2{
  font-size:22px;
  margin-bottom:15px;
}

.footer_text p{
  font-size:14px;
  color:#83888f;
  margin-bottom:20px;
}

.footer_text button{
  background:#0e8784;
  border:none;
  color:white;
  padding:12px 24px;
  border-radius:8px;
  font-weight:700;
}


 .header3 {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 30px 40px;
  }

  .logo3 img {
    width: 160px;
  }

  .header3 nav {
    display: flex;
    gap: 24px;
  }

  .header3 nav a {
    font-size: 14px;
    letter-spacing: 1px;
  }

  .social-icons {
    display: flex;
    gap: 16px;
  }

}
.social-icons a{
  color: white;
  margin-left:15px;
  font-size:18px;
}















@media (max-width: 768px) {

  body{
    padding: 0;
    margin: 0;
  }

  .navbar nav{
    display: none;
  }

  .navbar{
    display: flex;
    justify-content: space-between;
    padding: 20px;
  }

  .logo{
    margin-left: 40px;
  }

  .photo{
    padding: 20px;
  }

  .hero{
    background-size: cover;
    border-radius: 15px;
    padding: 30px 20px;
    text-align: left;
    margin-top: 100px;
  }

  .hero h1{
   font-size: 32px;
   line-height: 1.2;
   font-family: Fraunces;
   font-weight: 900;
   font-style: Black;
   font-size: 40px;
   line-height: 100%;
   letter-spacing: 0px;
   text-align: center;
   white-space:nowrap;
  }

  .hero p{
  font-size: 14px;
  line-height: 1.6;
  font-family: Barlow;
  font-weight: 400;
  font-style: Regular;
  font-size: 16px;
  line-height: 160%;
  letter-spacing: 0px;
  text-align: center;
  
  }

  .hero button{
  width: 100%;
  padding: 14px;
  font-size: 16px;
  background-color: var(--colors-teal-600, rgba(14, 135, 132, 1));
  font-family: Fraunces;
  font-weight: 900;
  font-style: Black;
  font-size: 18px;
  line-height: 140%;
  letter-spacing: 0px;
  text-align: center;
  }

  .headline h1{
    text-align: center;
    font-size: 30px;
    white-space: nowrap;
  }

  .Images{
    display: flex;
    flex-direction: column;
    gap: 40px;
    align-items: center;
  }

  .text img{
    width: 180px;
  }

  .text h3{
    font-size: 20px;
  }

  .text p{
    font-size: 14px;
  }

  .boxs{
    padding: 20px;
  }

  .card{
    padding: 25px 15px;
    border-radius: 15px;
  }

  .card p{
   font-family: Barlow;
   font-weight: 400;
   font-style: Regular;
   font-size: 16px;
   line-height: 160%;
   letter-spacing: 0px;
   text-align: center;

  }

  .cards{
    display: flex;
    flex-direction: column;
    gap: 20px;
  }

  .logos{
    padding: 20px;
    border-radius: 15px;
  }

  .logos h4{
    font-family: Fraunces;
    font-weight: 900;
    font-style: Black;
    font-size: 24px;
    line-height: 150%;
    letter-spacing: 0px;
    text-align: center;
  }

  .logos p{
    font-family: Barlow;
    font-weight: 400;
    font-style: Regular;
    font-size: 16px;
    line-height: 160%;
    letter-spacing: 0px;
    text-align: center;
  }

  .line{
    display: none;
  }
 
  .circle{
    display: none;
  }

  .number {
    display: none;
  }

  .footer_text {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    gap: 90px;
    padding: 20px;
    margin-top:30px;
  }

  .footer_text div {
    position: relative;
    max-width: 300px;
  }

  .footer_text div:nth-child(1)::before,
  .footer_text div:nth-child(2)::before,
  .footer_text div:nth-child(3)::before {
    position: absolute;
    top: -60px;
    left: 50%;
    transform: translateX(-50%);
    font-size: 60px;
    color: rgba(253, 214, 186, 1) ;
    font-weight: bold;
  }

  .footer_text div:nth-child(1)::before { content: "01"; }
  .footer_text div:nth-child(2)::before { content: "02"; }
  .footer_text div:nth-child(3)::before { content: "03"; }


  .footer h3{
    margin-top: 600px;
    text-align: center;
    font-family: Fraunces;
    font-weight: 900;
    font-style: Black;
    font-size: 24px;
    line-height: 150%;
    letter-spacing: 0px;
    text-align: center;
    color: var(--colors-neutral-500, rgba(131, 136, 143, 1));

  }

  .footer_text h2 {
    font-size: 24px;
    margin-top: 20px;
    font-family: Fraunces;
   font-weight: 900;
   font-style: Black;
   font-size: 32px;
   line-height: 113.99999999999999%;
   letter-spacing: 0px;
   text-align: center;
   color: var(--colors-neutral-900, rgba(51, 61, 75, 1));

  }

  .footer_text p {
    font-size: 14px;
    line-height: 1.8;
    color: var(--colors-neutral-900, rgba(51, 61, 75, 1));
    font-family: Barlow;
    font-weight: 400;
    font-style: Regular;
    font-size: 16px;
    line-height: 160%;
    letter-spacing: 0px;
    text-align: center;
  }

  .footer_text button {
   display: none;
  }

  .header3 {
    height: 30vh;
    flex-direction: column;
    align-items: center;
    justify-content:center ;
    gap: 40px;
  }

  .header3 nav {
    flex-direction: column;
    gap: 10px;
    font-family: Barlow;
    font-weight: 700;
    font-style: Bold;
    font-size: 12px; 
    line-height: 130%;
    letter-spacing: 0.92px;
    text-transform: uppercase;
    white-space: nowrap;
  }
}

        </header>
</body>
</html>
