
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>𝙽𝚞𝚎𝚜𝚝𝚛𝚘 𝚙𝚛𝚒𝚖𝚎𝚛 𝚊𝚗̃𝚘</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(to bottom, #ff758c, #ff7eb3);
    color: white;
    text-align: center;
    overflow-x: hidden;
}

section {
    padding: 60px 20px;
    opacity: 0;
    transform: translateY(30px);
    transition: 1s;
}

section.visible {
    opacity: 1;
    transform: translateY(0);
}

h1 { font-size: 2.5em; margin-bottom: 10px; }

.btn {
    background: white;
    color: #ff4d6d;
    padding: 15px 30px;
    border-radius: 30px;
    border: none;
    cursor: pointer;
    font-size: 18px;
    margin-top: 20px;
    font-weight: bold;
    box-shadow: 0 4px 15px rgba(0,0,0,0.2);
}

.gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
}

.gallery img {
    width: 90%;
    max-width: 280px;
    border-radius: 15px;
    transition: transform 0.3s;
    box-shadow: 0 4px 15px rgba(0,0,0,0.3);
}

#contador {
    font-size: 22px;
    font-weight: bold;
    margin: 20px auto;
    background: rgba(255, 255, 255, 0.25);
    padding: 20px;
    border-radius: 20px;
    display: inline-block;
    backdrop-filter: blur(5px);
}

.corazon {
    position: fixed;
    top: -10px;
    color: white;
    animation: caer 5s linear infinite;
    z-index: 999;
    pointer-events: none;
}

@keyframes caer { to { transform: translateY(110vh); } }

.hidden { display: none; }
</style>
</head>

<body>

<audio id="musica" loop>
    <source src="musica.mp3" type="audio/mpeg">
</audio>

<section class="visible">
    <h1>𝙽𝚞𝚎𝚜𝚝𝚛𝚘 𝚙𝚛𝚒𝚖𝚎𝚛 𝚊𝚗̃𝚘 𝚓𝚞𝚗𝚝𝚘𝚜💗</h1>
    <p>24 - El día donde lo nuestro empezó</p>
    <button class="btn" onclick="iniciarTodo()">Puchale 😀</button>
</section>

<section id="historia">
    <h2>como lo nuestro empezó</h2>
    <p>Ese día donde nos cruzamos por primera vez me dejaste abobado con tus ojazos. No me cabía la idea de que nuestros caminos se fueran a cruzar una segunda vez, pero aquí estamos, demostrando que algunas historias están escritas para no terminarse nunca.</p>
</section>

<div class="seccion-contador">
    <h1>Cada segundo a tu lado...</h1>
    <div id="contador">Calculando...</div>
</div>

<section>
    <h2>unas cuantas fotos y videos de este añito juntos </h2>
    <div class="gallery">
      <div class="gallery">
    <img src="A.jpg">
    <img src="B.jpg">
    <img src="C.jpg">
    <img src="D.jpg">
    <img src="E.jpg">
    <img src="F.jpg">
    <img src="G.jpg">
    <img src="H.jpg">
    <img src="I.jpg">
    <img src="J.jpg">
    <img src="K.jpg">
    <img src="L.jpg">
    <img src="M.jpg">
    <img src="N.jpg">
    <img src="O.jpg">
</div>
</section>

<section id="carta-amor">
    <div style="background: rgba(255, 255, 255, 0.15); padding: 30px; border-radius: 20px; max-width: 700px; margin: 0 auto; line-height: 1.8; backdrop-filter: blur(5px); border: 1px solid rgba(255,255,255,0.2);">
        <p>
            Muchas gracias por este año tan especial a tu lado. Me gustaría seguir caminando contigo hasta donde la vida nos lleve, en los momentos buenos y también en los difíciles, cuando todo salga bien y cuando no tanto.
        </p>
        <p>
            Quiero estar para ti en cada etapa, apoyarte, escucharte y crecer juntos. Y si en algún momento tenemos problemas, me gustaría que los enfrentemos juntos, porque no quiero perderte.
        </p>
        <p style="font-weight: bold; font-size: 1.1em;">
            Eres de lo más valioso que tengo. Llegaste a mi vida y me diste una nueva forma de ver las cosas. Gracias a ti, hoy tengo más ganas de seguir adelante… y me gustaría que sea contigo.
        </p>
    </div>
</section>

<section>
    <h2> 𝚎𝚜𝚙𝚎𝚛𝚘 𝚝𝚎 𝚑𝚊𝚢𝚊 𝚐𝚞𝚜𝚝𝚊𝚍𝚘 𝚕𝚎 𝚑𝚎𝚌𝚑𝚎 𝚐𝚊𝚗𝚒𝚝𝚊𝚜💗💗💗 </h2>
    <p> Un último mensajito, mi amor quiero que sepas que estoy aquí para ti, para lo que necesites y en cualquier momento. No estás sola, cuentas conmigo siempre.  

En los días buenos voy a celebrar contigo, y en los días difíciles voy a quedarme a tu lado para apoyarte y darte fuerzas. Puedes confiar en mí, en lo que siento y en que siempre voy a intentar hacerte sentir bien.  
<p>
No tienes que cargar todo tú sola porque estoy contigo, hoy, mañana ,pasado o hasta cuando no nos entendamos demasiado .💗💗 </p>
    <button class="btn" onclick="mostrarSorpresa()">No presiones esto</button>
    <p id="sorpresa" class="hidden">Sabía que lo ibas a hacer y por eso te voy a dar jaksjajaja te amo muchísimo pero si te voy a dar 😏😘</p>

<section id="ahora si un ultimo mensajito ">
    <h2>Un último detalle❤️</h2>
    <p>Antes de que te vayas, quería decirte que eres lo mejor que me ha pasado.🫶🏼😛💗💗</p>
    

<button class="btn" id="btnSorpresa" onclick="lanzarFinal()">
    <p>Cuando nos veamos abrázame y apriétame fuerte la verga para prometerme amarnos para siempre 🙀💗
          <p> otra cosa Si llegamos a tener hijos el primer nombre yo lo escojo🫶🏼🫶🏼 </p>
        </h1>
        <p style="font-size: 1.3em;">Prometo cuidarte y amarte cada día.Hasta que mi corazón deje de latir y sea lo que haya después también prometo cuidarte y amarte.💗✨😛</p>
        <div style="font-size: 70px;">💗</div>
    </div>
</section>

<script>
function iniciarTodo() {
    const musica = document.getElementById("musica");
    musica.play();

    document.getElementById("historia").scrollIntoView({ behavior: "smooth" });
}

const sections = document.querySelectorAll("section");
window.addEventListener("scroll", () => {
    sections.forEach(sec => {
        const top = sec.getBoundingClientRect().top;
        if (top < window.innerHeight - 100) {
            sec.classList.add("visible");
        }
    });
});


const fechaInicio = new Date("2025-04-24T00:00:00");

function actualizarContador() {
    const ahora = new Date();
    const diff = ahora - fechaInicio;

    const d = Math.floor(diff / (1000 * 60 * 60 * 24));
    const h = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const m = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
    const s = Math.floor((diff % (1000 * 60)) / 1000);

    document.getElementById("contador").innerHTML = 
        `${d} días, ${h}h, ${m}m y ${s}s juntos ❤️`;
}
setInterval(actualizarContador, 1000);
actualizarContador();

function mostrarSorpresa() {
    document.getElementById("sorpresa").classList.remove("hidden");
}


setInterval(() => {
    const gota = document.createElement("div");
    gota.classList.add("corazon"); 

    
   
    const variedad = ["❤️", "✨", "🌸", "💖", "⭐", "🌷", "💕", "✨"];
    gota.innerHTML = variedad[Math.floor(Math.random() * variedad.length)];
    
    gota.style.left = Math.random() * 100 + "vw";
    gota.style.fontSize = (Math.random() * 20 + 15) + "px";
    gota.style.opacity = Math.random() * 0.8 + 0.2;
    
    
    gota.style.animationDuration = (Math.random() * 3 + 4) + "s";
    
    document.body.appendChild(gota);
    
    setTimeout(() => { gota.remove(); }, 5000);
}, 350);
</script>

</body>
</html>
