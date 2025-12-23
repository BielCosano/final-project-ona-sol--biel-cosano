index.html
  <section class="Home">
    <div class="container">
        <h1 class="main">Quina cançó té més escoltes?</h1>
        <p class="buto"><a href="joc.html">JUGAR!</a></p>
        <img class="boles" src="img/boles.svg" alt="boles decoratives">
        <img class="fletxes" src="img/fletxes.svg" alt="fletxes decoratives">
        <img class="linia1" src="img/linia1.svg" alt="linia decorativa1">
        <img class="linia2" src="img/linia2.svg" alt="linia decorativa2">
        <img class="spotify" src="img/spotify.svg" alt="logo de spotify">
        <img class="wrappedlogo"    src="img/wrappedlogo.svg" alt="logo de spotify wrapped">
    </div>
</section>

final.html
<html lang="ca">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Has perdut!</title>
    <link rel="stylesheet" href="styles/css.css">
</head>
<body> 
    <main class="main">
      <h1>Has perdut!</h1>
      <p class="score">Puntuació: <strong>10/20</strong></p>

      <button class="buto">
        Compartir puntuació!
      </button>
    </main>
    <div class="img">
        <img class="boles2" src="img/boles.svg" alt="boles decoratives">
        <img class="boles3" src="img/boles.svg" alt="boles decoratives">
        <img class="fletxes2" src="img/fletxes.svg" alt="fletxes decoratives">
        <img class="linia3" src="img/linia3.svg" alt="linia decorativa1">
        <img class="linia4" src="img/linia4.svg" alt="linia decorativa2">
        <img class="spotify2" src="img/spotify.svg" alt="logo de spotify">
        <img class="wrappedlogo2" src="img/wrappedlogo.svg" alt="logo de spotify wrapped">
    
  </div>
</body>
</html>



styles
  .boles {
    position: absolute;
    top: 0;
    right: 0;
}
.fletxes {
    position: absolute;
    bottom: 51px;
    left: 70px;
}
.linia1 {
    position: absolute;
    top: 700px;
    left: 500px;
}
.linia2 {
    position: absolute;
    top: -80px;
    left: -50px;
}
.spotify {
    position: absolute;
    top: 700px;
    left: 1280px;
}

.wrappedlogo {
	position: absolute;
	top: 70px;
	left: 70px;
}

/* Center page content and style the play button to match the mockup */
.Home {
	min-height: 100vh;
	display: flex;
	align-items: center;
	justify-content: center;
}

.Home .main {
	margin: 0 0 18px;
	color: var(--color-negre);
}

.buto {
	display: flex;
	justify-content: center;
	width: 100%;
	margin-top: 6px;
}

.buto a {
	display: inline-block;
	background: var(--color-vermell);
	color: #ffffff;
	padding: 18px 56px;
	border-radius: 18px;
	font-weight: 900;
	text-decoration: none;
	letter-spacing: 0.08em;
	font-size: 48px;
}

.buto a:active {
	transform: translateY(2px);
}

.boles2 {
	position: absolute;
    top: -226px;
    right: 390px;
}
.boles3 {
	position: absolute;
    top: -226px;
    right: 765px;
}

.fletxes2 {
	position: absolute;
	top: 257px;
	right: 550px;
}

.linia3 {
	position: absolute;
	top: 0px;
	left: -50px;
}
.linia4 {
	position: absolute;
	top: 320px;
	left: 550px;
}
.spotify2 {
	position: absolute;
	top: 20px;
	left: 1330px;
}
.wrappedlogo2 {
	position: absolute;
	top: 700px;
	left: 52px;
}
.main{
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	margin-top: 200px;
	position: relative;
	gap: 24px;
}


