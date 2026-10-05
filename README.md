<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>AuraX Montañismo GT</title>

<style>

:root{
    --cyan:#5CE1E6;
    --black:#050607;
    --white:#FFFFFF;
    --gray:#AEB7BC;
}

*{
    box-sizing:border-box;
    margin:0;
    padding:0;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:Arial, Helvetica, sans-serif;
    background:#050607;
    color:white;
    line-height:1.6;
}

a{
    text-decoration:none;
    color:white;
}

img{
    max-width:100%;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
}


/* =========================
   MENU
========================= */

nav{
    position:sticky;
    top:0;
    z-index:100;
    background:rgba(5,6,7,.92);
    backdrop-filter:blur(12px);
    border-bottom:1px solid rgba(92,225,230,.25);
}

.nav-container{
    height:80px;
    display:flex;
    align-items:center;
    justify-content:space-between;
}

.logo img{
    width:160px;
}

.menu{
    display:flex;
    gap:30px;
}

.menu a{
    font-weight:bold;
    transition:.3s;
}

.menu a:hover{
    color:var(--cyan);
}

.btn{
    padding:12px 22px;
    background:var(--cyan);
    color:black;
    border-radius:30px;
    font-weight:bold;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-2px);
    box-shadow:0 0 20px rgba(92,225,230,.4);
}


/* =========================
   HERO
========================= */

.hero{
    min-height:85vh;

    background:
    linear-gradient(
        90deg,
        rgba(0,0,0,.95) 0%,
        rgba(0,0,0,.75) 45%,
        rgba(0,0,0,.15) 100%
    ),
    url("hoodie-aurax.jpg");

    background-size:cover;
    background-position:center;

    display:flex;
    align-items:center;
}

.hero-content{
    max-width:700px;
}

.small-title{
    color:var(--cyan);
    font-weight:bold;
    letter-spacing:3px;
    text-transform:uppercase;
}

.hero h1{
    font-size:70px;
    line-height:1;
    margin:15px 0 25px;
}

.hero h1 span{
    color:var(--cyan);
}

.hero p{
    font-size:22px;
    color:#D6DEE2;
    margin-bottom:30px;
}


/* =========================
   SECCIONES
========================= */

section{
    padding:90px 0;
}

.title{
    margin-bottom:40px;
}

.title h2{
    font-size:48px;
}

.title p{
    color:var(--gray);
    max-width:700px;
}


/* =========================
   PRODUCTOS
========================= */

.products{
    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:20px;
}

.card{
    background:#0D1114;
    border:1px solid rgba(92,225,230,.25);
    border-radius:20px;
    padding:30px;
    transition:.3s;
}

.card:hover{
    transform:translateY(-5px);
    border-color:var(--cyan);
}

.card-icon{
    font-size:55px;
    margin-bottom:20px;
}

.card h3{
    font-size:26px;
    margin-bottom:10px;
}

.card p{
    color:var(--gray);
}


/* =========================
   PROMOCIÓN
========================= */

.promotion{
    background:#080B0D;
}

.promo-box{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:50px;
    align-items:center;

    border:1px solid rgba(92,225,230,.3);
    padding:40px;
    border-radius:30px;

    background:
    linear-gradient(
        135deg,
        rgba(92,225,230,.12),
        rgba(92,225,230,.02)
    );
}

.promo-box img{
    border-radius:20px;
}

.promo-box h2{
    font-size:55px;
    line-height:1.05;
}

.promo-box h2 span{
    color:var(--cyan);
}

.promo-box p{
    color:#D6DEE2;
    font-size:20px;
    margin:20px 0 30px;
}


/* =========================
   MASCOTA / MARCA
========================= */

.brand-section{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:60px;
    align-items:center;
}

.brand-section img{
    border-radius:25px;
    border:1px solid rgba(92,225,230,.3);
}

.brand-text h2{
    font-size:50px;
    line-height:1.1;
}

.brand-text h2 span{
    color:var(--cyan);
}

.brand-text p{
    color:var(--gray);
    font-size:19px;
    margin-top:20px;
}


/* =========================
   VALORES
========================= */

.values{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:15px;
    margin-top:35px;
}

.value{
    background:#0D1114;
    border:1px solid rgba(92,225,230,.25);
    padding:20px;
    border-radius:15px;
}

.value strong{
    color:var(--cyan);
    display:block;
    margin-bottom:5px;
}


/* =========================
   CONTACTO
========================= */

.contact{
    text-align:center;

    background:
    radial-gradient(
        circle at top,
        rgba(92,225,230,.15),
        transparent 50%
    );
}

.contact h2{
    font-size:60px;
}

.contact p{
    color:var(--gray);
    font-size:19px;
    max-width:700px;
    margin:15px auto 30px;
}

.social-buttons{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:15px;
}

.social{
    padding:14px 25px;
    border-radius:30px;
    border:1px solid rgba(255,255,255,.3);
    transition:.3s;
}

.social:hover{
    border-color:var(--cyan);
    color:var(--cyan);
}


/* =========================
   FOOTER
========================= */

footer{
    border-top:1px solid rgba(92,225,230,.25);
    padding:30px 0;
    color:#8F999F;
}

.footer{
    display:flex;
    justify-content:space-between;
    flex-wrap:wrap;
    gap:20px;
}


/* =========================
   RESPONSIVE
========================= */

@media(max-width:900px){

    .menu{
        display:none;
    }

    .hero h1{
        font-size:50px;
    }

    .products{
        grid-template-columns:1fr;
    }

    .promo-box{
        grid-template-columns:1fr;
    }

    .brand-section{
        grid-template-columns:1fr;
    }

    .values{
        grid-template-columns:1fr 1fr;
    }

}

@media(max-width:550px){

    .hero h1{
        font-size:42px;
    }

    .title h2{
        font-size:36px;
    }

    .values{
        grid-template-columns:1fr;
    }

    .contact h2{
        font-size:40px;
    }

}

</style>
</head>


<body>


<!-- =========================
     MENU
========================= -->

<nav>

<div class="container nav-container">

<div class="logo">

<img src="logo-aurax.png"
alt="AuraX Montañismo GT">

</div>

<div class="menu">

<a href="#inicio">Inicio</a>

<a href="#coleccion">Colección</a>

<a href="#promocion">Promoción</a>

<a href="#aurax">AuraX</a>

<a href="#contacto">Contacto</a>

</div>

<a class="btn"
href="https://wa.me/50254342015"
target="_blank">

Comprar

</a>

</div>

</nav>



<!-- =========================
     PORTADA
========================= -->

<section id="inicio" class="hero">

<div class="container">

<div class="hero-content">

<div class="small-title">

AuraX Montañismo GT · Merch Outdoor

</div>

<h1>

Lleva la
<span>aventura</span>
contigo.

</h1>

<p>

Hoodies, camisetas, gorras, mochilas,
termos y accesorios inspirados en
la montaña, la naturaleza y la aventura.

</p>

<a class="btn"
href="#coleccion">

Ver colección

</a>

</div>

</div>

</section>



<!-- =========================
     COLECCIÓN
========================= -->

<section id="coleccion">

<div class="container">

<div class="title">

<div class="small-title">

Colección AuraX

</div>

<h2>

Merch para vivir la montaña.

</h2>

<p>

Productos diseñados para quienes quieren
llevar su espíritu aventurero más allá del sendero.

</p>

</div>


<div class="products">


<div class="card">

<div class="card-icon">
🧥
</div>

<h3>
Hoodies y camisetas
</h3>

<p>

Diseños AuraX inspirados en
montañas, aventura y naturaleza.

</p>

</div>



<div class="card">

<div class="card-icon">
🎒
</div>

<h3>
Mochilas
</h3>

<p>

Productos para acompañarte
en tus actividades y aventuras outdoor.

</p>

</div>



<div class="card">

<div class="card-icon">
🥤
</div>

<h3>
Gorras, termos y accesorios
</h3>

<p>

Detalles que permiten llevar
la identidad AuraX todos los días.

</p>

</div>


</div>

</div>

</section>



<!-- =========================
     PROMOCIÓN
========================= -->

<section id="promocion"
class="promotion">

<div class="container">

<div class="promo-box">


<div>

<div class="small-title">

Promoción AuraX

</div>

<h2>

Tu primera compra
<span>tiene premio.</span>

</h2>

<p>

Compra tu primer hoodie AuraX
y recibe un llavero de regalo.

Promoción válida mientras
existan unidades disponibles.

</p>

<a class="btn"
href="https://wa.me/50254342015"
target="_blank">

Quiero mi Hoodie

</a>

</div>


<div>

<img
src="hoodie-aurax.jpg"
alt="Hoodie AuraX">

</div>


</div>

</div>

</section>



<!-- =========================
     AURAX
========================= -->

<section id="aurax">

<div class="container brand-section">


<div>

<img
src="mascota-aurax.jpg"
alt="Mascota oficial AuraX">

</div>


<div class="brand-text">

<div class="small-title">

Identidad AuraX

</div>

<h2>

Más que merch.

<span>
Es una forma de vivir la montaña.
</span>

</h2>

<p>

AuraX nace de la conexión con la naturaleza,
la aventura y la superación personal.

Nuestra marca busca crear productos
que representen a quienes disfrutan explorar,
descubrir nuevos lugares y mantener vivo
su espíritu aventurero.

</p>


<div class="values">


<div class="value">

<strong>
Aventura
</strong>

Explorar y descubrir nuevos caminos.

</div>


<div class="value">

<strong>
Identidad
</strong>

Un estilo propio y reconocible.

</div>


<div class="value">

<strong>
Naturaleza
</strong>

Respeto por los lugares que nos inspiran.

</div>


<div class="value">

<strong>
Comunidad
</strong>

Unir personas que comparten
la pasión por la montaña.

</div>


</div>

</div>

</div>

</section>



<!-- =========================
     CONTACTO
========================= -->

<section id="contacto"
class="contact">

<div class="container">

<div class="small-title">

AuraX Montañismo GT

</div>

<h2>

¿Listo para lucir AuraX?

</h2>

<p>

Consulta productos, tallas,
disponibilidad y promociones.

Síguenos en nuestras redes
o realiza tu pedido directamente
por WhatsApp.

</p>


<div class="social-buttons">


<a
class="btn"
href="https://wa.me/50254342015"
target="_blank">

WhatsApp 5434 2015

</a>


<a
class="social"
href="https://www.instagram.com/aurax_gt"
target="_blank">

Instagram @aurax_gt

</a>


<a
class="social"
href="https://www.tiktok.com/@aurax546"
target="_blank">

TikTok @aurax546

</a>


</div>

</div>

</section>



<!-- =========================
     FOOTER
========================= -->

<footer>

<div class="container footer">

<div>

© 2026 AuraX Montañismo GT

</div>

<div>

Más que caminar, vivir la montaña.

</div>

</div>

</footer>


</body>
</html>
