<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<title>Una Carta Para Ti</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Caveat:wght@400;600;700&family=Cinzel:wght@400;600&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}

/* ═══════════════════════════════════
   ROOT & BODY
═══════════════════════════════════ */
:root {
  --paper: #e8cc7a;
  --paper2: #d4b05a;
  --ink: #12080200;
  --burn: rgba(28,10,1,0.72);
  --wax: #8b0d0d;
}

html { height: 100%; }

body {
  min-height: 100%;
  background: #080503;
  background-image:
    repeating-linear-gradient(91deg,transparent,transparent 2px,rgba(255,190,80,.012) 2px,rgba(255,190,80,.012) 3px),
    repeating-linear-gradient(180deg,transparent,transparent 38px,rgba(0,0,0,.05) 38px,rgba(0,0,0,.05) 39px),
    radial-gradient(ellipse at 40% 30%,#1a0e06 0%,#070402 60%,#000 100%);
  display: flex;
  flex-direction: column;
  align-items: center;
  font-family: 'Caveat', cursive;
  padding: 0;
  overflow-x: hidden;
}

/* Vignette */
body::before {
  content:'';
  position:fixed;inset:0;
  background:radial-gradient(ellipse at center,transparent 15%,rgba(0,0,0,.65) 65%,rgba(0,0,0,.96) 100%);
  pointer-events:none;z-index:0;
}

/* Candle glow */
.glow {
  position:fixed;inset:0;pointer-events:none;z-index:1;
  background:radial-gradient(ellipse 55% 45% at 50% 50%,rgba(255,150,35,.07) 0%,transparent 70%);
  animation:flicker 3s ease-in-out infinite alternate;
}
@keyframes flicker{
  0%{opacity:.45}25%{opacity:1}55%{opacity:.6}80%{opacity:.88}100%{opacity:.72}
}

/* Floating dust */
.dust{position:fixed;inset:0;pointer-events:none;z-index:1;overflow:hidden}
.dp{
  position:absolute;border-radius:50%;
  background:rgba(210,175,90,.55);
  animation:rise linear infinite;
}
@keyframes rise{
  0%{transform:translateY(110vh) scale(0);opacity:0}
  8%{opacity:1}92%{opacity:.55}
  100%{transform:translateY(-8vh) translateX(var(--dx)) scale(1.3);opacity:0}
}

/* ═══════════════════════════════════
   ENVELOPE SCREEN (initial state)
═══════════════════════════════════ */
#env-screen {
  position:fixed;inset:0;
  display:flex;flex-direction:column;
  align-items:center;justify-content:center;
  z-index:50;
  transition:opacity .8s ease, transform .8s ease;
}
#env-screen.hide {
  opacity:0;
  transform:scale(.85) translateY(30px);
  pointer-events:none;
}

.env-wrap {
  position:relative;
  width:min(290px,84vw);
  cursor:pointer;
  transform-style:preserve-3d;
  perspective:1000px;
  animation:hb 2.8s ease-in-out infinite;
}
.env-wrap.stop{animation:none;pointer-events:none}

@keyframes hb{
  0%,100%{transform:scale(1) rotate(-.5deg)}
  14%{transform:scale(1.05) rotate(.3deg)}
  28%{transform:scale(1) rotate(-.2deg)}
  42%{transform:scale(1.04) rotate(.2deg)}
  70%{transform:scale(1) rotate(-.3deg)}
}

/* Envelope body */
.env-body {
  position:relative;
  width:100%;padding-bottom:65%;
  transform-style:preserve-3d;
}

.env-bg {
  position:absolute;inset:0;
  border-radius:3px 3px 8px 8px;
  background:
    radial-gradient(ellipse 22% 14% at 20% 60%,rgba(75,38,5,.26) 0%,transparent 100%),
    radial-gradient(ellipse 15% 10% at 74% 28%,rgba(60,30,3,.22) 0%,transparent 100%),
    linear-gradient(148deg,#c8a058 0%,#dbb874 10%,#c4a05e 22%,#dfc080 36%,#c9a86a 50%,#b88e4e 63%,#d3b46e 76%,#bf985a 88%,#a77840 100%);
  box-shadow:
    0 0 0 1.5px rgba(72,34,6,.55),
    0 8px 32px rgba(0,0,0,.8),
    0 16px 55px rgba(0,0,0,.55),
    inset 0 0 55px rgba(50,20,3,.24);
  overflow:hidden;
}
.env-bg::before{
  content:'';position:absolute;inset:0;
  background-image:
    repeating-linear-gradient(0deg,transparent,transparent 5px,rgba(88,45,5,.05) 5px,rgba(88,45,5,.05) 6px),
    repeating-linear-gradient(90deg,transparent,transparent 7px,rgba(68,34,3,.04) 7px,rgba(68,34,3,.04) 8px);
  pointer-events:none;
}
.env-bg::after{
  content:'';position:absolute;inset:0;border-radius:inherit;
  box-shadow:
    inset 0 0 22px 12px rgba(25,9,1,.72),
    inset 0 0 6px 3px rgba(15,4,0,.85);
  pointer-events:none;
}

/* Crease lines SVG */
.env-svg{position:absolute;inset:0;pointer-events:none;z-index:3}
.env-svg svg{width:100%;height:100%}

/* Flap */
.env-flap{
  position:absolute;top:0;left:0;right:0;height:57%;
  transform-origin:top center;
  transform-style:preserve-3d;
  z-index:18;
  clip-path:polygon(0% 0%,50% 100%,100% 0%);
  background:
    radial-gradient(ellipse 30% 20% at 20% 78%,rgba(72,36,5,.28) 0%,transparent 100%),
    linear-gradient(174deg,#d4b06a 0%,#e8ca80 18%,#caa060 44%,#dab870 70%,#b89050 100%);
  filter:drop-shadow(0 5px 14px rgba(0,0,0,.52));
  transition:transform 1.05s cubic-bezier(.4,0,.2,1) .8s;
}
.env-flap::after{
  content:'';position:absolute;inset:0;
  box-shadow:inset 0 0 18px 9px rgba(26,9,1,.6);
  pointer-events:none;
}
.env-flap.open{transform:rotateX(-185deg)}

/* Wax seal */
.seal-wrap{
  position:absolute;top:50%;left:50%;
  transform:translate(-50%,-50%);
  z-index:25;transform-style:preserve-3d;
  transition:transform .55s cubic-bezier(.34,1.56,.64,1),opacity .35s ease .46s;
}
.seal-wrap.pop{
  transform:translate(-50%,-50%) scale(1.7) translateZ(120px);
  opacity:0;pointer-events:none;
}
.seal{
  width:clamp(60px,17vw,76px);height:clamp(60px,17vw,76px);
  border-radius:50%;position:relative;
  display:flex;align-items:center;justify-content:center;
  background:
    radial-gradient(circle at 30% 27%,rgba(255,110,110,.4) 0%,transparent 44%),
    radial-gradient(circle at 68% 72%,rgba(0,0,0,.44) 0%,transparent 54%),
    radial-gradient(circle at 50% 50%,#bf1e18 0%,#8a0c0c 44%,#580808 68%,#360404 100%);
  box-shadow:
    0 0 0 2.5px #360404,
    0 0 0 4.5px rgba(72,6,6,.54),
    0 8px 28px rgba(0,0,0,.85),
    inset 0 3px 7px rgba(255,90,90,.3),
    inset 0 -4px 12px rgba(0,0,0,.56);
  cursor:pointer;
}
.seal::before{
  content:'';position:absolute;inset:-7px;border-radius:50%;
  background:
    radial-gradient(ellipse 22% 32% at 13% 92%,rgba(115,8,8,.92) 0%,transparent 74%),
    radial-gradient(ellipse 17% 28% at 82% 97%,rgba(105,7,7,.84) 0%,transparent 74%),
    radial-gradient(ellipse 13% 23% at 50% 103%,rgba(98,7,7,.9) 0%,transparent 74%),
    radial-gradient(ellipse 15% 21% at 3% 52%,rgba(110,8,8,.74) 0%,transparent 74%),
    radial-gradient(ellipse 15% 21% at 97% 47%,rgba(100,8,8,.74) 0%,transparent 74%);
  filter:blur(1.8px);z-index:-1;
}
.seal::after{
  content:'';position:absolute;inset:7px;border-radius:50%;
  border:1.5px solid rgba(198,70,70,.36);
  box-shadow:inset 0 0 7px rgba(0,0,0,.54);
}
.seal-txt{
  font-family:'Cinzel',serif;font-size:clamp(9px,2.4vw,12px);font-weight:600;
  color:rgba(255,175,175,.42);letter-spacing:3px;
  text-shadow:0 1px 3px rgba(0,0,0,.95);
  position:relative;z-index:2;user-select:none;
}

/* Tap hint */
.tap-hint{
  position:absolute;bottom:-42px;left:50%;transform:translateX(-50%);
  font-family:'Cinzel',serif;font-size:clamp(9px,2.5vw,11px);
  color:rgba(210,172,85,.65);letter-spacing:4px;
  text-transform:uppercase;white-space:nowrap;
  animation:pu 2.3s ease-in-out infinite;
}
@keyframes pu{0%,100%{opacity:.25}50%{opacity:1}}

/* ═══════════════════════════════════
   LETTER SCREEN (revealed state)
═══════════════════════════════════ */
#letter-screen {
  position:relative;z-index:10;
  width:100%;
  min-height:100vh;
  display:flex;
  flex-direction:column;
  align-items:center;
  padding:clamp(24px,6vw,52px) clamp(12px,4vw,24px) clamp(40px,10vw,80px);
  opacity:0;
  pointer-events:none;
  transition:opacity 1s ease;
}
#letter-screen.show {
  opacity:1;
  pointer-events:all;
}

/* ═══════════════════════════════════
   THE AGED PAPER LETTER
═══════════════════════════════════ */
.paper {
  position:relative;
  width:100%;
  max-width:520px;

  /* ─── AGED PAPER BASE ─── */
  background:
    /* Coffee ring stain — top right */
    radial-gradient(ellipse 26% 16% at 80% 11%,rgba(86,46,8,.24) 55%,transparent 100%),
    radial-gradient(ellipse 22% 13% at 82% 13%,transparent 50%,rgba(86,46,8,.12) 51%,transparent 68%),
    /* Coffee ring stain — bottom left */
    radial-gradient(ellipse 32% 19% at 16% 78%,rgba(68,34,6,.28) 55%,transparent 100%),
    radial-gradient(ellipse 26% 15% at 18% 81%,transparent 50%,rgba(68,34,6,.14) 51%,transparent 68%),
    /* Small third stain center-ish */
    radial-gradient(ellipse 14% 9% at 55% 46%,rgba(76,38,6,.14) 0%,transparent 100%),
    /* Humidity / tide lines at edges */
    radial-gradient(ellipse 68% 28% at 50% 2%,rgba(95,52,10,.16) 0%,transparent 100%),
    radial-gradient(ellipse 44% 22% at 90% 94%,rgba(76,40,7,.18) 0%,transparent 100%),
    /* Edge darkening (absorbed moisture) */
    radial-gradient(ellipse 100% 22% at 50% 100%,rgba(55,24,3,.28) 0%,transparent 100%),
    radial-gradient(ellipse 22% 100% at 0%   50%,rgba(52,22,3,.2) 0%,transparent 100%),
    radial-gradient(ellipse 22% 100% at 100% 50%,rgba(52,22,3,.2) 0%,transparent 100%),
    radial-gradient(ellipse 100% 20% at 50% 0%,rgba(55,24,3,.22) 0%,transparent 100%),
    /* Base old paper tones — very irregular */
    linear-gradient(
      158deg,
      #f2d87e 0%,  #e6c86e 7%,
      #f4dea0 16%, #dec464 28%,
      #ecd08a 39%, #d6b25c 50%,
      #f0d68c 60%, #e2c274 70%,
      #ccaa50 80%, #c49c4c 89%,
      #d8b76a 100%
    );

  border-radius:2px 5px 3px 4px;
  padding:clamp(22px,6vw,42px) clamp(20px,5.5vw,38px) clamp(28px,8vw,52px);

  /* Heavy burnt/aged shadow */
  box-shadow:
    6px 8px 0 rgba(0,0,0,.1),
    -3px 4px 0 rgba(0,0,0,.07),
    0 12px 48px rgba(0,0,0,.72),
    0 3px 14px rgba(0,0,0,.58),
    inset 0 0 40px 20px rgba(42,16,2,.34),
    inset 0 0 10px 5px rgba(22,8,0,.56);

  /* Slight tilt — authentic */
  transform:rotate(-.4deg);

  /* Animation: slides in from below */
  animation: none;
}

/* Paper fiber texture overlay */
.paper::before {
  content:'';
  position:absolute;inset:0;border-radius:inherit;
  background-image:
    repeating-linear-gradient(0deg,  transparent,transparent 25px,rgba(92,52,8,.08) 25px,rgba(92,52,8,.08) 26px),
    repeating-linear-gradient(90deg, transparent,transparent 3px, rgba(72,40,5,.033) 3px, rgba(72,40,5,.033) 4px),
    repeating-linear-gradient(150deg,transparent,transparent 18px,rgba(52,26,2,.025) 18px,rgba(52,26,2,.025) 19px);
  pointer-events:none;z-index:0;
}

/* Fold crease lines */
.fold-h {
  position:absolute;left:0;right:0;top:34%;height:2px;
  background:linear-gradient(90deg,transparent 0%,rgba(72,36,5,.22) 8%,rgba(92,50,7,.34) 50%,rgba(72,36,5,.22) 92%,transparent 100%);
  pointer-events:none;z-index:1;
}
.fold-h2 {
  position:absolute;left:0;right:0;top:67%;height:1.5px;
  background:linear-gradient(90deg,transparent 0%,rgba(68,33,4,.16) 8%,rgba(85,46,6,.26) 50%,rgba(68,33,4,.16) 92%,transparent 100%);
  pointer-events:none;z-index:1;
}

/* Burnt edges */
.paper-burn {
  position:absolute;inset:0;border-radius:inherit;
  box-shadow:
    inset 0   0  28px 16px rgba(28,9,1,.62),
    inset 0   0   8px  5px rgba(16,5,0,.8),
    inset  4px  4px 16px 8px rgba(32,12,2,.34),
    inset -4px -4px 16px 8px rgba(32,12,2,.34);
  pointer-events:none;z-index:2;
}

/* Foxing / aging spots */
.fox {
  position:absolute;border-radius:50%;pointer-events:none;z-index:1;
  background:radial-gradient(circle,rgba(82,40,6,.42) 0%,transparent 70%);
}

/* ─── LETTER CONTENT ─── */
.letter-inner { position:relative;z-index:3; }

/* Header */
.lh {
  text-align:center;
  margin-bottom:clamp(14px,4vw,22px);
  padding-bottom:clamp(12px,3.5vw,18px);
  border-bottom:1.5px solid rgba(75,40,7,.3);
}
.lh-date {
  display:block;
  font-family:'Caveat',cursive;
  font-size:clamp(12px,3.2vw,15px);
  color:rgba(35,14,3,.52);
  font-style:italic;margin-bottom:4px;
}
.lh-sub {
  font-family:'Cinzel',serif;
  font-size:clamp(8px,2.2vw,10px);
  color:rgba(72,36,7,.42);letter-spacing:5px;text-transform:uppercase;
}

/* Body */
.lb {
  font-family:'Caveat',cursive;
  font-size:clamp(16px,4.6vw,21px);
  line-height:1.88;
  color:#130a03;
  text-align:justify;
  hyphens:auto;
}
.lb p {
  margin-bottom:clamp(12px,3.5vw,18px);
  text-indent:clamp(20px,5.5vw,30px);
}
.lb em  { font-style:normal; color:rgba(22,10,2,.72); }
.lb strong { font-weight:700; color:#0c0602; }

.lb .question {
  display:block;
  margin-top:clamp(10px,3vw,16px);
  font-size:clamp(17px,5vw,23px);
  font-weight:700;
  color:rgba(90,16,16,.92);
  text-align:center;
  text-indent:0!important;
  font-style:italic;
}

/* Divider */
.divider {
  text-align:center;
  font-size:clamp(10px,2.2vw,12px);
  color:rgba(85,42,8,.4);
  letter-spacing:7px;
  margin:clamp(10px,3vw,16px) 0;
}

/* Footer */
.lf {
  margin-top:clamp(14px,4vw,22px);
  text-align:right;
  border-top:1px solid rgba(72,38,7,.22);
  padding-top:clamp(10px,3vw,15px);
}
.lf-pre {
  display:block;
  font-family:'Caveat',cursive;
  font-size:clamp(13px,3.5vw,16px);
  color:rgba(26,10,3,.58);
  font-style:italic;margin-bottom:2px;
}
.lf-name {
  display:block;
  font-family:'Caveat',cursive;
  font-size:clamp(21px,5.8vw,30px);
  font-weight:700;color:#0c0602;line-height:1.1;
}
.lf-hearts {
  display:block;
  color:rgba(105,16,16,.72);
  font-size:clamp(14px,3.6vw,18px);
  letter-spacing:7px;margin-top:5px;
}

/* Roses / ambient */
.rose {
  position:fixed;pointer-events:none;z-index:5;
  font-size:clamp(26px,7vw,40px);
  opacity:0;
  filter:drop-shadow(0 4px 16px rgba(110,8,8,.6));
  transition:opacity 1.2s ease;
  animation:rf ease-in-out infinite;
}
.rose.show{opacity:.65}
@keyframes rf{0%,100%{transform:translateY(0) rotate(-6deg)}50%{transform:translateY(-14px) rotate(7deg)}}

/* ─── PARA ENTRADA DE LA CARTA ─── */
.paper.entering {
  animation: slideIn 1.1s cubic-bezier(.22,.68,0,1.2) forwards;
}
@keyframes slideIn {
  0%  { opacity:0; transform:rotate(-.4deg) translateY(60px) scale(.96); }
  100%{ opacity:1; transform:rotate(-.4deg) translateY(0) scale(1); }
}

/* Párrafos con entrada de tinta */
.lb p, .lb .question, .lf, .lh {
  opacity:0;
  animation:ink .85s ease forwards;
}
.lh              { animation-delay: .4s; }
.lb p:nth-child(1){ animation-delay: .65s; }
.lb p:nth-child(2){ animation-delay: .95s; }
.lb p:nth-child(3){ animation-delay:1.25s; }
.lb p:nth-child(4){ animation-delay:1.55s; }
.lb .question    { animation-delay:1.82s; }
.divider         { opacity:0; animation:ink .85s ease 1.95s forwards; }
.lf              { animation-delay:2.1s; }

@keyframes ink {
  from{opacity:0;transform:translateY(6px);filter:blur(.8px)}
  to  {opacity:1;transform:translateY(0);filter:blur(0)}
}

/* ─── Estado oculto inicial de la carta ─── */
#letter-screen.hidden-init * {
  animation-play-state: paused;
}
</style>
</head>
<body>

<div class="dust" id="dust"></div>
<div class="glow"></div>

<!-- ROSES -->
<div class="rose" id="r1" style="top:6%;left:2%;animation-duration:4.4s;animation-delay:0s;">🥀</div>
<div class="rose" id="r2" style="top:8%;right:3%;animation-duration:3.8s;animation-delay:.6s;">🥀</div>
<div class="rose" id="r3" style="bottom:8%;left:3%;animation-duration:4.9s;animation-delay:1s;">🌹</div>
<div class="rose" id="r4" style="bottom:10%;right:3%;animation-duration:4.2s;animation-delay:1.5s;">🥀</div>

<!-- ══════════════════════════════
     ENVELOPE SCREEN
══════════════════════════════ -->
<div id="env-screen">
  <div class="env-wrap" id="envWrap">
    <div class="tap-hint">· toca para abrir ·</div>
    <div class="env-body">

      <!-- Envelope background -->
      <div class="env-bg">
        <div class="env-svg">
          <svg viewBox="0 0 300 195" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
            <line x1="0"   y1="195" x2="150" y2="0"   stroke="rgba(62,28,4,.24)" stroke-width="1"/>
            <line x1="300" y1="195" x2="150" y2="0"   stroke="rgba(62,28,4,.24)" stroke-width="1"/>
            <polygon points="0,195 150,105 0,42"    fill="rgba(72,33,4,.11)"/>
            <polygon points="300,195 150,105 300,42" fill="rgba(55,24,3,.09)"/>
          </svg>
        </div>
      </div>

      <!-- Flap -->
      <div class="env-flap" id="flap"></div>

      <!-- Seal -->
      <div class="seal-wrap" id="sealWrap">
        <div class="seal"><span class="seal-txt">LOVE</span></div>
      </div>

    </div><!-- /env-body -->
  </div><!-- /env-wrap -->
</div><!-- /env-screen -->

<!-- ══════════════════════════════
     LETTER SCREEN (full page)
══════════════════════════════ -->
<div id="letter-screen" class="hidden-init">

  <!-- THE LETTER -->
  <div class="paper" id="thePaper">
    <!-- Aged overlays -->
    <div class="fold-h"></div>
    <div class="fold-h2"></div>
    <div class="paper-burn"></div>

    <!-- Foxing / aging spots scattered -->
    <div class="fox" style="width:22px;height:14px;top:9%;left:6%;transform:rotate(22deg)"></div>
    <div class="fox" style="width:13px;height:9px;top:18%;right:10%;transform:rotate(-14deg)"></div>
    <div class="fox" style="width:9px;height:6px;top:31%;left:14%;transform:rotate(38deg);opacity:.6"></div>
    <div class="fox" style="width:18px;height:12px;top:44%;right:8%;transform:rotate(-22deg);opacity:.7"></div>
    <div class="fox" style="width:11px;height:8px;top:56%;left:7%;transform:rotate(15deg)"></div>
    <div class="fox" style="width:26px;height:16px;top:7%;right:6%;transform:rotate(9deg);opacity:.58"></div>
    <div class="fox" style="width:8px;height:6px;top:70%;right:22%;transform:rotate(-30deg);opacity:.72"></div>
    <div class="fox" style="width:15px;height:10px;top:82%;left:18%;transform:rotate(42deg);opacity:.65"></div>
    <div class="fox" style="width:7px;height:5px;top:91%;right:14%;transform:rotate(-18deg);opacity:.55"></div>
    <div class="fox" style="width:12px;height:8px;top:38%;left:3%;transform:rotate(28deg);opacity:.5"></div>

    <div class="letter-inner">

      <!-- Header -->
      <div class="lh">
        <span class="lh-date">En algún lugar del tiempo…</span>
        <span class="lh-sub">— para ti —</span>
      </div>

      <!-- Body -->
      <div class="lb">
        <p>Sé que tal vez no vengo del mismo lugar del que tú vienes, ni tengo las costumbres o modos del medio en que tú estás. Pero lo único de lo que tengo certeza es de <em>lo que yo siento</em>, y lo que llegué a sentir por ti — que ha sido lo más lindo y sincero que he llegado a sentir por alguien <strong>en mucho tiempo.</strong></p>

        <p>No me lastimas ni nada por el estilo. Al contrario, me das <strong>paz y tranquilidad</strong> en mi vida, la cual es un caos. Eres como ese <em>rayito de luz en la oscuridad.</em> Yo lo quiero realmente intentar contigo, a pesar de los riesgos que — créeme — en mi vida he tomado muchos… y tú vales <strong>totalmente</strong> la pena.</p>

        <p>No me importa que sea a escondidas; la verdad eso me da igual, mientras en tu corazón y ojos pueda estar yo, porque tú <em>sí</em> estás en el mío. Podemos ser como Ulises y Renata, pero <strong>sin que te mueras,</strong> paro banda. Tampoco te voy a decir que todo va a ser perfecto, pero con problemas, días buenos y días malos — lo quiero intentar y lograr <em>contigo.</em></p>

        <p>Ya estamos grandes, ya sabemos lo que queremos. Y yo <strong>te quiero</strong> y te elijo a ti para que seas mi compañera en esto llamado vida. No te digo amor eterno ni nada de eso, pero sí <em>luchar cada día</em> para que esto dure un día más. He aprendido a luchar por las cosas que valen la pena y <strong>no guardarme lo que siento.</strong></p>

        <span class="question">¿Pero tú también quieres eso?</span>
      </div>

      <div class="divider">✦ &nbsp; ♡ &nbsp; ✦</div>

      <!-- Footer -->
      <div class="lf">
        <span class="lf-pre">Con todo lo que soy,</span>
        <span class="lf-name">Siempre tuyo ♡</span>
        <span class="lf-hearts">♥ · ♥ · ♥</span>
      </div>

    </div><!-- /letter-inner -->
  </div><!-- /paper -->

</div><!-- /letter-screen -->

<script>
/* ── Dust particles ── */
(function(){
  const c=document.getElementById('dust');
  for(let i=0;i<36;i++){
    const p=document.createElement('div');
    p.className='dp';
    const sz=1+Math.random()*3.2,
          dur=10+Math.random()*18,
          del=Math.random()*16,
          dx=((Math.random()-.5)*120)+'px';
    p.style.cssText=`left:${Math.random()*100}%;width:${sz}px;height:${sz}px;animation-duration:${dur}s;animation-delay:-${del}s;--dx:${dx};opacity:${.12+Math.random()*.52}`;
    c.appendChild(p);
  }
})();

/* ── Envelope interaction ── */
const envScreen   = document.getElementById('env-screen');
const letterScreen= document.getElementById('letter-screen');
const flap        = document.getElementById('flap');
const sealWrap    = document.getElementById('sealWrap');
const envWrap     = document.getElementById('envWrap');
const roses       = [1,2,3,4].map(n=>document.getElementById('r'+n));
let opened = false;

function openIt(){
  if(opened)return;
  opened=true;
  envWrap.classList.add('stop');

  // 1. Seal pops
  setTimeout(()=>sealWrap.classList.add('pop'), 0);

  // 2. Flap opens
  setTimeout(()=>flap.classList.add('open'), 600);

  // 3. Envelope fades out
  setTimeout(()=>envScreen.classList.add('hide'), 1600);

  // 4. Letter screen appears — full page, scrollable
  setTimeout(()=>{
    letterScreen.classList.remove('hidden-init');
    letterScreen.classList.add('show');
    document.getElementById('thePaper').classList.add('entering');
    roses.forEach(r=>r.classList.add('show'));
    // allow body to scroll now
    document.body.style.overflow='auto';
  }, 1850);
}

envWrap.addEventListener('click', openIt);
envWrap.addEventListener('touchstart', e=>{ e.preventDefault(); openIt(); }, {passive:false});

// Body scroll locked until letter reveals
document.body.style.overflow='hidden';
</script>
</body>
</html>
