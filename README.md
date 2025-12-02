# hungarianspirit
<!DOCTYPE html>
<html lang="hu">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pálinka Fusion - Hungarian Spirit</title>
<style>
/* --- ALAP BEÁLLÍTÁSOK ÉS STÍLUSOK --- */
:root {
--primary-color: #2E7D32; /* Méregzöld - Természet */
--accent-color: #C62828; /* Piros - Szenvedély */
--bg-light: #F9F9F9;
--text-dark: #333;
--white: #ffffff;
}
body {
font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
margin: 0;
padding: 0;
color: var(--text-dark);
background-color: var(--bg-light);
line-height: 1.6;
}
h1, h2, h3 {
margin-top: 0;
font-weight: 700;
letter-spacing: -0.5px;
}
/* --- HERO SZEKCIÓ (MOBILRA) --- */
.hero {
background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
url('https://images.unsplash.com/photo-1514362545857-3bc16549766b?ixlib=rb-1.2.1&auto=for
mat&fit=crop&w=800&q=80');
background-size: cover;
background-position: center;
height: 90vh; /* Majdnem teljes képernyő */
display: flex;
flex-direction: column;
justify-content: center;
align-items: center;
text-align: center;
color: var(--white);
padding: 20px;
}
.hero h1 {
font-size: 2.5rem;
margin-bottom: 10px;
text-transform: uppercase;
border-bottom: 3px solid var(--accent-color);
display: inline-block;
padding-bottom: 5px;
}
.hero p {
font-size: 1.2rem;
margin-bottom: 30px;
font-weight: 300;
}
.btn {
background-color: var(--accent-color);
color: var(--white);
padding: 15px 30px;
text-decoration: none;
border-radius: 50px;
font-weight: bold;
text-transform: uppercase;
font-size: 1rem;
box-shadow: 0 4px 15px rgba(0,0,0,0.3);
transition: transform 0.2s;
}
.btn:active {
transform: scale(0.95);
}
/* --- STORY SZEKCIÓ --- */
.section {
padding: 60px 20px;
text-align: center;
}
.story {
background-color: var(--white);
}
.quote {
font-style: italic;
font-size: 1.2rem;
color: #555;
border-left: 4px solid var(--primary-color);
padding-left: 15px;
margin: 20px auto;
max-width: 400px;
text-align: left;
}
/* --- RECEPT KÁRTYA --- */
.recipe-card {
background: #fff;
border-radius: 15px;
box-shadow: 0 10px 30px rgba(0,0,0,0.1);
padding: 30px 20px;
margin: 20px 0;
text-align: left;
border-top: 5px solid var(--primary-color);
}
.ingredient-list {
list-style: none;
padding: 0;
}
.ingredient-list li {
margin-bottom: 15px;
font-size: 1.1rem;
display: flex;
align-items: center;
}
.icon {
margin-right: 10px;
font-size: 1.5rem;
}
/* --- KIHÍVÁS --- */
.challenge {
background-color: #222;
color: var(--white);
}
.hashtag {
color: #FFD700; /* Arany */
font-size: 1.5rem;
font-weight: bold;
display: block;
margin-bottom: 20px;
}
/* --- HELYSZÍNEK --- */
.locations ul {
list-style: none;
padding: 0;
}
.locations li {
background: #e8f5e9;
margin: 10px 0;
padding: 15px;
border-radius: 8px;
font-weight: bold;
color: var(--primary-color);
}
/* --- LÁBLÉC --- */
footer {
background-color: #111;
color: #888;
text-align: center;
padding: 40px 20px;
font-size: 0.9rem;
}
/* --- FLAG DECORATION --- */
.flag-bar {
height: 6px;
width: 100%;
display: flex;
}
.red { background: #C62828; flex: 1; }
.white { background: #fff; flex: 1; }
.green { background: #2E7D32; flex: 1; }
</style>
</head>
<body>
<div class="flag-bar">
<div class="red"></div>
<div class="white"></div>
<div class="green"></div>
</div>
<header class="hero">
<h1>Pálinka Fusion</h1>
<p>A Magyar Signature Koktél</p>
<a href="#recept" class="btn">Kóstold meg</a>
</header>
<section class="section story">
<h2>A Magyar Lélek</h2>
<p>A <strong>Pálinka Fusion</strong> nem csak egy ital.
[span_0](start_span)Hungarikum, ami a magyar identitás részévé válik, akárcsak az Aperol
Spritz az olaszoknál.[span_0](end_span)</p>
<div class="quote">
[span_1](start_span)"A magyar lélek három színe: a tüzes pálinka, a frissítő természet,
a mézédes napfény."[span_1](end_span)
</div>
</section>
<section id="recept" class="section" style="background-color: #f4f4f4;">
<h2>Hungarian Spirit</h2>
<p>A standardizált recept. [span_2](start_span)Ugyanaz a minőség Berlinben, mint
Budapesten.[span_2](end_span)</p>
<div class="recipe-card">
<ul class="ingredient-list">
[span_3](start_span)<li><span class="icon">🥃</span> <strong>Alap:</strong>
Törköly pálinka (Hungarikum)[span_3](end_span)</li>
[span_4](start_span)<li><span class="icon">🍋</span> <strong>Íz:</strong> Lime és
Méz - édes & savanyú[span_4](end_span)</li>
[span_5](start_span)<li><span class="icon">💧</span> <strong>Lazítás:</strong>
Szódavíz[span_5](end_span)</li>
[span_6](start_span)<li><span class="icon">🌿</span> <strong>Díszítés:</strong>
Friss menta & citrus[span_6](end_span)</li>
</ul>
<p style="font-size: 0.9rem; color: #666; margin-top: 20px;">
[span_7](start_span)<em>Tálalás: Jeges, hosszú pohárban, piros-fehér-zöld
díszítéssel.[span_7](end_span)</em>
</p>
</div>
</section>
<section class="section challenge">
<h2>Csatlakozz!</h2>
<span class="hashtag">#HungarianSpiritChallenge</span>
[span_8](start_span)<p>Keresd a fesztiválokon, fotózd le a jellegzetes poharat és oszd
meg a TikTokon[span_8](end_span)!</p>
<a href="#" class="btn" style="background: #fff; color: #333;">Irány a TikTok</a>
</section>
<section class="section locations">
<h2>Hol találod?</h2>
<p>Fesztiválok és világvárosok:</p>
<ul>
[span_9](start_span)<li>🎪 Sziget Fesztivál & Balaton Sound[span_9](end_span)</li>
[span_10](start_span)<li>󰎲 Berlin - Magyar Bárok[span_10](end_span)</li>
[span_11](start_span)<li>󰏅 London - Magyar Éttermek[span_11](end_span)</li>
[span_12](start_span)<li>󰑔 New York - Partnerhelyek[span_12](end_span)</li>
</ul>
</section>
<section class="section" style="background-color: #e0f7fa;">
<h3>Vendéglátós vagy?</h3>
<p>Legyél hivatalos partner! Garantált minőség és marketing támogatás.</p>
<a href="mailto:partner@palinkafusion.hu" style="color: #006064; font-weight:
bold;">Kapcsolatfelvétel →</a>
</section>
<footer>
<p>© 2024 Pálinka Fusion<br>A mértékletes alkoholfogyasztás fontossága.</p>
</footer>
</body>
</html>
