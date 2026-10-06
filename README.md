<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AURAX GT | Montañismo, Senderismo y Expediciones en Guatemala</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: League Spartan -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <!-- Lucide Icons CDN -->
    <script src="https://unpkg.com/lucide@latest"></script>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        aurax: {
                            neon: '#00D2FE',
                            dark: '#070A0D',
                            card: '#12181B',
                            cardBorder: '#1F292E',
                            white: '#FFFFFF'
                        }
                    },
                    fontFamily: {
                        spartan: ['"League Spartan"', 'sans-serif']
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'League Spartan', sans-serif;
            background-color: #070A0D;
            color: #FFFFFF;
        }
        .text-glow {
            text-shadow: 0 0 15px rgba(0, 210, 254, 0.6);
        }
        .border-glow {
            box-shadow: 0 0 20px rgba(0, 210, 254, 0.25);
        }
        .bg-glow {
            background: radial-gradient(circle at center, rgba(0,210,254,0.12) 0%, transparent 70%);
        }
    </style>
</head>
<body class="bg-[#070A0D] text-white antialiased selection:bg-aurax-neon selection:text-black">

    <!-- BARRA DE NAVEGACIÓN -->
    <nav class="fixed top-0 w-full z-50 bg-[#070A0D]/90 backdrop-blur-md border-b border-aurax-cardBorder">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            
            <!-- LOGO SVG OFICIAL AURAX -->
            <a href="#" class="flex items-center space-x-3 group">
                <svg class="h-10 w-auto" viewBox="0 0 450 160" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <!-- Montañas traseras -->
                    <path d="M10 120 L80 40 L130 90 L180 20 L260 120 Z" fill="none" stroke="#FFFFFF" stroke-width="4" stroke-linejoin="round"/>
                    <path d="M140 120 L210 30 L290 120 Z" fill="none" stroke="#FFFFFF" stroke-width="3" stroke-linejoin="round"/>
                    <path d="M250 120 L310 50 L380 120 Z" fill="none" stroke="#FFFFFF" stroke-width="4" stroke-linejoin="round"/>
                    <!-- Nieve picos -->
                    <path d="M80 40 L65 60 L80 55 L95 65 Z" fill="#FFFFFF"/>
                    <path d="M180 20 L160 45 L180 40 L200 50 Z" fill="#FFFFFF"/>
                    <!-- Texto AURA -->
                    <text x="30" y="115" font-family="'League Spartan', sans-serif" font-weight="900" font-size="62" fill="#FFFFFF" letter-spacing="4">AURA</text>
                    <!-- X Estilizada Manuscrita en Cian Neón -->
                    <path d="M230 45 C 245 75, 270 115, 305 135 M 295 55 C 275 80, 245 110, 215 130" stroke="#00D2FE" stroke-width="10" stroke-linecap="round" filter="drop-shadow(0px 0px 8px #00D2FE)"/>
                    <!-- Subtítulo MONTAÑISMO GT -->
                    <text x="35" y="145" font-family="'League Spartan', sans-serif" font-weight="800" font-size="19" fill="#FFFFFF" letter-spacing="7">MONTAÑISMO GT</text>
                </svg>
            </a>

            <!-- MENÚ PRINCIPAL -->
            <div class="hidden lg:flex space-x-7 text-xs font-bold tracking-widest uppercase">
                <a href="#identidad" class="hover:text-aurax-neon transition-colors">Nosotros</a>
                <a href="#expediciones" class="hover:text-aurax-neon transition-colors">Expediciones</a>
                <a href="#cotizador" class="hover:text-aurax-neon transition-colors">Cotizador</a>
                <a href="#checklist" class="hover:text-aurax-neon transition-colors">Checklist</a>
                <a href="#guardian" class="hover:text-aurax-neon transition-colors">Espíritu</a>
                <a href="#contacto" class="hover:text-aurax-neon transition-colors">Contacto</a>
            </div>

            <!-- CTA BOTÓN WHATSAPP -->
            <a href="https://wa.me/50254342015?text=Hola%20AURAX%20GT,%20quiero%20informaci%C3%B3n%20sobre%20sus%20pr%C3%B3ximas%20expediciones" target="_blank" class="inline-flex items-center gap-2 px-5 py-2.5 rounded-full border border-aurax-neon text-aurax-neon font-bold text-xs tracking-widest hover:bg-aurax-neon hover:text-black transition-all shadow-lg hover:shadow-aurax-neon/30">
                <i data-lucide="message-circle" class="w-4 h-4"></i>
                <span class="hidden sm:inline">RESERVAR POR WA</span>
            </a>
        </div>
    </nav>

    <!-- HERO SECTION -->
    <section class="pt-32 pb-20 md:pt-44 md:pb-32 px-4 relative overflow-hidden border-b border-aurax-cardBorder">
        <div class="absolute inset-0 bg-glow pointer-events-none"></div>
        <div class="max-w-5xl mx-auto text-center relative z-10">
            
            <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-aurax-card border border-aurax-neon/40 text-aurax-neon text-xs font-bold tracking-widest mb-6 shadow-sm">
                <i data-lucide="compass" class="w-4 h-4"></i> DESDE QUETZALTENANGO (XELA) PARA EL MUNDO
            </div>

            <h1 class="text-4xl sm:text-6xl md:text-7xl font-black tracking-tight uppercase mb-6 leading-none">
                Conquista tu propia cumbre, <br>
                <span class="text-aurax-neon text-glow">el límite eres tú</span>
            </h1>

            <p class="text-lg md:text-xl text-gray-300 max-w-3xl mx-auto font-normal leading-relaxed mb-8">
                "Cuando la ciudad hace demasiado ruido... la montaña tiene la respuesta." <br>
                <span class="text-sm text-gray-400">Más que caminar, vivir la montaña. Conquistando a Guate desde lo alto.</span>
            </p>

            <div class="flex flex-col sm:flex-row gap-4 justify-center items-center">
                <a href="#expediciones" class="w-full sm:w-auto px-8 py-4 rounded-xl bg-aurax-neon text-black font-extrabold tracking-wider text-sm hover:bg-white transition-all shadow-lg shadow-aurax-neon/20">
                    VER PRÓXIMAS SALIDAS
                </a>
                <a href="#cotizador" class="w-full sm:w-auto px-8 py-4 rounded-xl border border-white/20 hover:border-aurax-neon text-white font-extrabold tracking-wider text-sm hover:text-aurax-neon transition-all">
                    COTIZAR GRUPO PRIVADO
                </a>
            </div>

            <!-- REDES SOCIALES RÁPIDAS -->
            <div class="mt-10 flex justify-center items-center gap-6 text-gray-400 text-sm font-bold">
                <a href="https://www.instagram.com/aurax_gt" target="_blank" class="flex items-center gap-2 hover:text-aurax-neon transition-colors">
                    <i data-lucide="instagram" class="w-5 h-5 text-aurax-neon"></i> @aurax_gt
                </a>
                <a href="https://www.tiktok.com/@aurax546" target="_blank" class="flex items-center gap-2 hover:text-aurax-neon transition-colors">
                    <i data-lucide="video" class="w-5 h-5 text-aurax-neon"></i> @aurax546
                </a>
                <a href="https://wa.me/50254342015" target="_blank" class="flex items-center gap-2 hover:text-aurax-neon transition-colors">
                    <i data-lucide="phone" class="w-5 h-5 text-aurax-neon"></i> +502 5434-2015
                </a>
            </div>
        </div>
    </section>

    <!-- IDENTIDAD Y FILOSOFÍA (MISIÓN, VISIÓN, OBJETIVOS, ORIGEN) -->
    <section id="identidad" class="py-20 px-4 max-w-7xl mx-auto">
        <div class="text-center mb-16">
            <h2 class="text-xs font-bold tracking-[0.3em] text-aurax-neon uppercase mb-2">Manifiesto de Marca</h2>
            <h3 class="text-3xl md:text-5xl font-black uppercase">Misión, Visión y Nuestra Historia</h3>
        </div>

        <!-- MISIÓN, VISIÓN, PROPÓSITO -->
        <div class="grid md:grid-cols-3 gap-8 mb-16">
            <div class="bg-aurax-card border border-aurax-cardBorder p-8 rounded-2xl relative hover:border-aurax-neon/50 transition-all">
                <div class="w-12 h-12 rounded-xl bg-aurax-neon/10 border border-aurax-neon/30 flex items-center justify-center text-aurax-neon mb-6">
                    <i data-lucide="target" class="w-6 h-6"></i>
                </div>
                <h4 class="text-xl font-black uppercase mb-3 text-aurax-neon">Misión</h4>
                <p class="text-gray-300 text-sm leading-relaxed">
                    Brindar experiencias de montañismo, senderismo y ascenso de volcanes que inspiren a las personas a conectar con la naturaleza, superar sus propios límites y crear vínculos a través de la aventura, promoviendo siempre la seguridad, el respeto ecológico y el compañerismo.
                </p>
            </div>

            <div class="bg-aurax-card border border-aurax-cardBorder p-8 rounded-2xl relative hover:border-aurax-neon/50 transition-all">
                <div class="w-12 h-12 rounded-xl bg-aurax-neon/10 border border-aurax-neon/30 flex items-center justify-center text-aurax-neon mb-6">
                    <i data-lucide="eye" class="w-6 h-6"></i>
                </div>
                <h4 class="text-xl font-black uppercase mb-3 text-aurax-neon">Visión</h4>
                <p class="text-gray-300 text-sm leading-relaxed">
                    Ser la comunidad líder de montañismo y aventura en Guatemala, reconocida por ofrecer experiencias auténticas, seguras y memorables, promoviendo una cultura de exploración responsable y convirtiéndose en referente regional.
                </p>
            </div>

            <div class="bg-aurax-card border border-aurax-cardBorder p-8 rounded-2xl relative hover:border-aurax-neon/50 transition-all">
                <div class="w-12 h-12 rounded-xl bg-aurax-neon/10 border border-aurax-neon/30 flex items-center justify-center text-aurax-neon mb-6">
                    <i data-lucide="shield-check" class="w-6 h-6"></i>
                </div>
                <h4 class="text-xl font-black uppercase mb-3 text-aurax-neon">Objetivos</h4>
                <p class="text-gray-300 text-sm leading-relaxed">
                    Organizar ascensos con altos estándares de planificación y seguridad, promover la convivencia comunitaria, educar sobre el turismo responsable y consolidar una marca referente en el montañismo guatemalteco.
                </p>
            </div>
        </div>

        <!-- ORIGEN XELA & MODELO DIGITAL -->
        <div class="grid md:grid-cols-2 gap-8 bg-aurax-card border border-aurax-cardBorder rounded-2xl p-8">
            <div>
                <span class="text-xs font-bold text-aurax-neon tracking-widest uppercase">Nuestros Orígenes</span>
                <h4 class="text-2xl font-black uppercase mb-4 mt-1">Nacidos en Quetzaltenango (Xela)</h4>
                <p class="text-gray-300 text-sm leading-relaxed mb-4">
                    AURAX GT nació por la visión de un entrenador de ejercicio funcional en Quetzaltenango que decidió llevar a sus atletas fuera del gimnasio para desafiar la cumbre del Volcán Santa María.
                </p>
                <p class="text-gray-300 text-sm leading-relaxed">
                    Lo que comenzó como una prueba de resistencia física se convirtió en un movimiento de reconexión mental, expandiéndose hacia caminatas comunitarias, expediciones nacionales e internacionales.
                </p>
            </div>

            <div class="border-t md:border-t-0 md:border-l border-aurax-cardBorder pt-6 md:pt-0 md:pl-8 flex flex-col justify-center">
                <span class="text-xs font-bold text-aurax-neon tracking-widest uppercase">Operación Innovadora</span>
                <h4 class="text-2xl font-black uppercase mb-4 mt-1">Modelo 100% Digital e Itinerante</h4>
                <p class="text-gray-300 text-sm leading-relaxed mb-4">
                    Sin ataduras de una tienda física tradicional: gestionamos reservas, consultas y atención personalizada a través de canales digitales.
                </p>
                <div class="space-y-2 text-xs font-bold text-gray-300">
                    <div class="flex items-center gap-2"><i data-lucide="check-circle" class="w-4 h-4 text-aurax-neon"></i> Reservas directas vía WhatsApp y Redes</div>
                    <div class="flex items-center gap-2"><i data-lucide="check-circle" class="w-4 h-4 text-aurax-neon"></i> Merchandising Oficial (Cilindros, Playeras, Parches)</div>
                    <div class="flex items-center gap-2"><i data-lucide="check-circle" class="w-4 h-4 text-aurax-neon"></i> Entregas en puntos de reunión o envíos a todo el país</div>
                </div>
            </div>
        </div>
    </section>

    <!-- GUARDIÁN MÍSTICO (LOBO NEÓN) -->
    <section id="guardian" class="py-20 px-4 bg-aurax-card border-y border-aurax-cardBorder">
        <div class="max-w-5xl mx-auto text-center">
            <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-black border border-aurax-neon/40 text-aurax-neon text-xs font-bold tracking-widest mb-6">
                <i data-lucide="zap" class="w-4 h-4"></i> ESPÍRITU DE COMUNIDAD
            </div>
            <h3 class="text-3xl md:text-5xl font-black uppercase mb-6">El Guardián Místico AURAX</h3>
            
            <div class="max-w-md mx-auto mb-8 relative">
                <div class="absolute inset-0 bg-aurax-neon/20 blur-2xl rounded-full"></div>
                <!-- ILUSTRACIÓN SVG DEL LOBO GUARDIÁN -->
                <svg class="w-64 h-64 mx-auto relative z-10" viewBox="0 0 200 200" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M100 20 L130 70 L170 80 L140 120 L150 170 L100 140 L50 170 L60 120 L30 80 L70 70 Z" stroke="#00D2FE" stroke-width="3" fill="#070A0D" stroke-linejoin="round" filter="drop-shadow(0px 0px 10px #00D2FE)"/>
                    <circle cx="80" cy="85" r="5" fill="#00D2FE"/>
                    <circle cx="120" cy="85" r="5" fill="#00D2FE"/>
                    <path d="M100 110 L90 125 L110 125 Z" fill="#00D2FE"/>
                    <path d="M20 180 L60 140 L100 180 L140 140 L180 180" stroke="#FFFFFF" stroke-width="2"/>
                </svg>
            </div>

            <p class="text-gray-300 text-base max-w-2xl mx-auto leading-relaxed">
                Representado por el **Lobo Neón sobre las cumbres volcánicas**, encarna la fuerza colectiva, el instinto de exploración, la lealtad de la manada y la templanza necesaria para conquistar la noche y la altitud.
            </p>
        </div>
    </section>

    <!-- PRÓXIMAS EXPEDICIONES Y TARIFAS REALES -->
    <section id="expediciones" class="py-20 px-4 max-w-7xl mx-auto">
        <div class="text-center mb-16">
            <h2 class="text-xs font-bold tracking-[0.3em] text-aurax-neon uppercase mb-2">Calendario de Cumbres</h2>
            <h3 class="text-3xl md:text-5xl font-black uppercase">Próximas Expediciones y Tarifas</h3>
        </div>

        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
            
            <!-- TARJETA 1 -->
            <div class="bg-aurax-card border border-aurax-cardBorder rounded-2xl p-6 hover:border-aurax-neon/60 transition-all flex flex-col justify-between">
                <div>
                    <div class="flex justify-between items-start mb-4">
                        <span class="px-3 py-1 rounded-full bg-aurax-neon/10 border border-aurax-neon/30 text-aurax-neon text-xs font-bold">Aventura Nocturna</span>
                        <span class="text-2xl font-black text-aurax-neon">Q270</span>
                    </div>
                    <h4 class="text-xl font-bold uppercase mb-2">Santiaguito Nocturno</h4>
                    <p class="text-gray-400 text-xs mb-4">Observación del complejo volcánico Santiaguito bajo las estrellas con vista panorámica desde el mirador.</p>
                </div>
                <a href="https://wa.me/50254342015?text=Deseo%20reservar%20mi%20lugar%20para%20el%20Santiaguito%20Nocturno%20(Q270)" target="_blank" class="w-full py-3 rounded-xl border border-aurax-neon text-aurax-neon font-bold text-xs tracking-widest text-center hover:bg-aurax-neon hover:text-black transition-all">
                    RESERVAR (Q270)
                </a>
            </div>

            <!-- TARJETA 2 -->
            <div class="bg-aurax-card border border-aurax-cardBorder rounded-2xl p-6 hover:border-aurax-neon/60 transition-all flex flex-col justify-between">
                <div>
                    <div class="flex justify-between items-start mb-4">
                        <span class="px-3 py-1 rounded-full bg-aurax-neon/10 border border-aurax-neon/30 text-aurax-neon text-xs font-bold">Ruta Local Xela</span>
                        <span class="text-2xl font-black text-aurax-neon">Q150</span>
                    </div>
                    <h4 class="text-xl font-bold uppercase mb-2">Volcán Santa María</h4>
                    <p class="text-gray-400 text-xs mb-4">Ascenso al gigante de Quetzaltenango (3,772 msnm). El origen y corazón de nuestra comunidad.</p>
                </div>
                <a href="https://wa.me/50254342015?text=Deseo%20reservar%20mi%20lugar%20para%20el%20Volc%C3%A1n%20Santa%20Mar%C3%ADa%20(Q150)" target="_blank" class="w-full py-3 rounded-xl border border-aurax-neon text-aurax-neon font-bold text-xs tracking-widest text-center hover:bg-aurax-neon hover:text-black transition-all">
                    RESERVAR (Q150)
                </a>
            </div>

            <!-- TARJETA 3 -->
            <div class="bg-aurax-card border border-aurax-cardBorder rounded-2xl p-6 hover:border-aurax-neon/60 transition-all flex flex-col justify-between">
                <div>
                    <div class="flex justify-between items-start mb-4">
                        <span class="px-3 py-1 rounded-full bg-aurax-neon/10 border border-aurax-neon/30 text-aurax-neon text-xs font-bold">Senderismo y Lago</span>
                        <span class="text-2xl font-black text-aurax-neon">Q220</span>
                    </div>
                    <h4 class="text-xl font-bold uppercase mb-2">Rostro Maya / Atitlán</h4>
                    <p class="text-gray-400 text-xs mb-4">Amanecer espectacular sobre el lago más bello del mundo desde la cumbre del Rostro Maya.</p>
                </div>
                <a href="https://wa.me/50254342015?text=Deseo%20reservar%20mi%20lugar%20para%20el%20Rostro%20Maya%20/ %20Atitl%C3%A1n%20(Q220)" target="_blank" class="w-full py-3 rounded-xl border border-aurax-neon text-aurax-neon font-bold text-xs tracking-widest text-center hover:bg-aurax-neon hover:text-black transition-all">
                    RESERVAR (Q220)
                </a>
            </div>

            <!-- TARJETA 4 -->
            <div class="bg-aurax-card border border-aurax-cardBorder rounded-2xl p-6 hover:border-aurax-neon/60 transition-all flex flex-col justify-between">
                <div>
                    <div class="flex justify-between items-start mb-4">
                        <span class="px-3 py-1 rounded-full bg-aurax-neon/10 border border-aurax-neon/30 text-aurax-neon text-xs font-bold">Alta Exigencia</span>
                        <span class="text-2xl font-black text-aurax-neon">Q450</span>
                    </div>
                    <h4 class="text-xl font-bold uppercase mb-2">Trilogía: Acatenango & Fuego</h4>
                    <p class="text-gray-400 text-xs mb-4">Acampada a gran altura presenciando las erupciones nocturnas del Volcán de Fuego.</p>
                </div>
                <a href="https://wa.me/50254342015?text=Deseo%20reservar%20mi%20lugar%20para%20Acatenango%20%26%20Fuego%20(Q450)" target="_blank" class="w-full py-3 rounded-xl border border-aurax-neon text-aurax-neon font-bold text-xs tracking-widest text-center hover:bg-aurax-neon hover:text-black transition-all">
                    RESERVAR (Q450)
                </a>
            </div>

            <!-- TARJETA 5 -->
            <div class="bg-aurax-card border border-aurax-cardBorder rounded-2xl p-6 hover:border-aurax-neon/60 transition-all flex flex-col justify-between md:col-span-2 lg:col-span-1">
                <div>
                    <div class="flex justify-between items-start mb-4">
                        <span class="px-3 py-1 rounded-full bg-aurax-neon/10 border border-aurax-neon/30 text-aurax-neon text-xs font-bold">Internacional</span>
                        <span class="text-2xl font-black text-aurax-neon">Q550</span>
                    </div>
                    <h4 class="text-xl font-bold uppercase mb-2">Ilamatepec (El Salvador)</h4>
                    <p class="text-gray-400 text-xs mb-4">Expedición internacional al majestuoso Volcán de Santa Ana con su laguna turquesa en el cráter.</p>
                </div>
                <a href="https://wa.me/50254342015?text=Deseo%20reservar%20mi%20lugar%20para%20Ilamatepec,%20El%20Salvador%20(Q550)" target="_blank" class="w-full py-3 rounded-xl border border-aurax-neon text-aurax-neon font-bold text-xs tracking-widest text-center hover:bg-aurax-neon hover:text-black transition-all">
                    RESERVAR (Q550)
                </a>
            </div>

        </div>
    </section>

    <!-- COTIZADOR DE EXPEDICIONES PRIVADAS -->
    <section id="cotizador" class="py-20 px-4 bg-aurax-card border-y border-aurax-cardBorder">
        <div class="max-w-4xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-xs font-bold tracking-[0.3em] text-aurax-neon uppercase mb-2">Simulador en Tiempo Real</h2>
                <h3 class="text-3xl md:text-5xl font-black uppercase">Cotizador de Expediciones Privadas</h3>
            </div>

            <div class="bg-black border border-aurax-cardBorder p-8 rounded-2xl space-y-8">
                
                <!-- DESTINO -->
                <div>
                    <label class="block text-xs font-bold uppercase tracking-wider text-aurax-neon mb-3">1. Selecciona el Destino</label>
                    <select id="cot-destino" onchange="calcularCotizacion()" class="w-full p-4 rounded-xl bg-aurax-card border border-aurax-cardBorder text-white text-sm focus:border-aurax-neon outline-none">
                        <option value="150">Volcán Santa María (Base: Q150/pers)</option>
                        <option value="220">Rostro Maya / Atitlán (Base: Q220/pers)</option>
                        <option value="270">Santiaguito Nocturno (Base: Q270/pers)</option>
                        <option value="450">Acatenango & Fuego (Base: Q450/pers)</option>
                        <option value="550">Ilamatepec, El Salvador (Base: Q550/pers)</option>
                    </select>
                </div>

                <!-- INTEGRANTES -->
                <div>
                    <div class="flex justify-between items-center mb-3">
                        <label class="text-xs font-bold uppercase tracking-wider text-aurax-neon">2. Número de Montañistas</label>
                        <span id="cot-num-display" class="font-bold text-lg text-aurax-neon">1 Persona</span>
                    </div>
                    <input type="range" id="cot-num" min="1" max="25" value="1" oninput="calcularCotizacion()" class="w-full accent-aurax-neon cursor-pointer">
                </div>

                <!-- EXTRAS -->
                <div>
                    <label class="block text-xs font-bold uppercase tracking-wider text-aurax-neon mb-3">3. Servicios Adicionales</label>
                    <div class="grid sm:grid-cols-2 gap-4">
                        <label class="flex items-center gap-3 p-4 rounded-xl bg-aurax-card border border-aurax-cardBorder cursor-pointer">
                            <input type="checkbox" id="cot-extra-dron" onchange="calcularCotizacion()" class="accent-aurax-neon w-5 h-5">
                            <span class="text-xs font-bold">Cobertura con Dron (+Q250 total)</span>
                        </label>
                        <label class="flex items-center gap-3 p-4 rounded-xl bg-aurax-card border border-aurax-cardBorder cursor-pointer">
                            <input type="checkbox" id="cot-extra-playera" onchange="calcularCotizacion()" class="accent-aurax-neon w-5 h-5">
                            <span class="text-xs font-bold">Playera Oficial AURAX (+Q100/p)</span>
                        </label>
                    </div>
                </div>

                <!-- TOTAL ESTIMADO -->
                <div class="p-6 rounded-xl bg-aurax-card border border-aurax-neon/40 flex flex-col sm:flex-row justify-between items-center gap-4">
                    <div>
                        <span class="text-xs text-gray-400 font-bold uppercase tracking-wider">Total Estimado en Quetzales</span>
                        <div id="cot-total" class="text-4xl font-black text-aurax-neon text-glow">Q150.00</div>
                    </div>
                    <button onclick="confirmarCotizacionWA()" class="w-full sm:w-auto px-8 py-4 rounded-xl bg-aurax-neon text-black font-extrabold text-xs tracking-widest hover:bg-white transition-all">
                        CONFIRMAR POR WHATSAPP
                    </button>
                </div>

            </div>
        </div>
    </section>

    <!-- CHECKLIST PACK ATTACK -->
    <section id="checklist" class="py-20 px-4 max-w-5xl mx-auto">
        <div class="text-center mb-12">
            <h2 class="text-xs font-bold tracking-[0.3em] text-aurax-neon uppercase mb-2">Preparación de Equipo</h2>
            <h3 class="text-3xl md:text-5xl font-black uppercase">Checklist de Mochila (Pack Attack)</h3>
            <p class="text-gray-400 text-sm mt-2">Marca el equipo obligatorio antes de subir a la montaña.</p>
        </div>

        <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-4">
            <label class="flex items-center gap-3 p-4 rounded-xl bg-aurax-card border border-aurax-cardBorder cursor-pointer hover:border-aurax-neon/50 transition-all">
                <input type="checkbox" class="accent-aurax-neon w-5 h-5">
                <span class="text-xs font-bold">Ropa en 3 capas (Térmica)</span>
            </label>
            <label class="flex items-center gap-3 p-4 rounded-xl bg-aurax-card border border-aurax-cardBorder cursor-pointer hover:border-aurax-neon/50 transition-all">
                <input type="checkbox" class="accent-aurax-neon w-5 h-5">
                <span class="text-xs font-bold">2 Litros de Agua / Suero</span>
            </label>
            <label class="flex items-center gap-3 p-4 rounded-xl bg-aurax-card border border-aurax-cardBorder cursor-pointer hover:border-aurax-neon/50 transition-all">
                <input type="checkbox" class="accent-aurax-neon w-5 h-5">
                <span class="text-xs font-bold">Linterna de Cabeza + Baterías</span>
            </label>
            <label class="flex items-center gap-3 p-4 rounded-xl bg-aurax-card border border-aurax-cardBorder cursor-pointer hover:border-aurax-neon/50 transition-all">
                <input type="checkbox" class="accent-aurax-neon w-5 h-5">
                <span class="text-xs font-bold">Calzado con labrado profundo</span>
            </label>
            <label class="flex items-center gap-3 p-4 rounded-xl bg-aurax-card border border-aurax-cardBorder cursor-pointer hover:border-aurax-neon/50 transition-all">
                <input type="checkbox" class="accent-aurax-neon w-5 h-5">
                <span class="text-xs font-bold">Snacks de alto valor calórico</span>
            </label>
            <label class="flex items-center gap-3 p-4 rounded-xl bg-aurax-card border border-aurax-cardBorder cursor-pointer hover:border-aurax-neon/50 transition-all">
                <input type="checkbox" class="accent-aurax-neon w-5 h-5">
                <span class="text-xs font-bold">Botiquín de uso personal</span>
            </label>
        </div>
    </section>

    <!-- FOOTER Y CONTACTO OFICIAL -->
    <footer id="contacto" class="py-16 border-t border-aurax-cardBorder bg-black">
        <div class="max-w-7xl mx-auto px-4 text-center space-y-8">
            <div class="flex justify-center">
                <svg class="h-12 w-auto" viewBox="0 0 450 160" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M10 120 L80 40 L130 90 L180 20 L260 120 Z" stroke="#FFFFFF" stroke-width="4"/>
                    <text x="30" y="115" font-family="'League Spartan', sans-serif" font-weight="900" font-size="62" fill="#FFFFFF">AURA</text>
                    <path d="M230 45 C 245 75, 270 115, 305 135 M 295 55 C 275 80, 245 110, 215 130" stroke="#00D2FE" stroke-width="10" stroke-linecap="round"/>
                    <text x="35" y="145" font-family="'League Spartan', sans-serif" font-weight="800" font-size="19" fill="#FFFFFF">MONTAÑISMO GT</text>
                </svg>
            </div>

            <!-- REDES OFICIALES Y TELÉFONO -->
            <div class="flex flex-wrap justify-center items-center gap-8 text-sm font-bold">
                <a href="https://wa.me/50254342015" target="_blank" class="flex items-center gap-2 hover:text-aurax-neon transition-colors">
                    <i data-lucide="phone" class="w-5 h-5 text-aurax-neon"></i> Tel / WA: 54342015
                </a>
                <a href="https://www.instagram.com/aurax_gt" target="_blank" class="flex items-center gap-2 hover:text-aurax-neon transition-colors">
                    <i data-lucide="instagram" class="w-5 h-5 text-aurax-neon"></i> Instagram: @aurax_gt
                </a>
                <a href="https://www.tiktok.com/@aurax546" target="_blank" class="flex items-center gap-2 hover:text-aurax-neon transition-colors">
                    <i data-lucide="video" class="w-5 h-5 text-aurax-neon"></i> TikTok: @aurax546
                </a>
            </div>

            <p class="text-xs text-gray-500">
                Quetzaltenango (Xela), Guatemala &bull; Operación 100% Digital e Itinerante
            </p>
            <p class="text-xs text-gray-600 font-mono">
                &copy; AURAX GT. Conquistando a Guate desde lo alto.
            </p>
        </div>
    </footer>

    <!-- LÓGICA INTERACTIVA EN JAVASCRIPT -->
    <script>
        // Inicializar íconos
        lucide.createIcons();

        function calcularCotizacion() {
            const precioBase = parseFloat(document.getElementById('cot-destino').value);
            const numPersonas = parseInt(document.getElementById('cot-num').value);
            const extraDron = document.getElementById('cot-extra-dron').checked ? 250 : 0;
            const extraPlayera = document.getElementById('cot-extra-playera').checked ? (100 * numPersonas) : 0;

            document.getElementById('cot-num-display').innerText = numPersonas === 1 ? '1 Persona' : `${numPersonas} Personas`;

            const subtotal = (precioBase * numPersonas) + extraDron + extraPlayera;
            document.getElementById('cot-total').innerText = `Q${subtotal.toFixed(2)}`;
        }

        function confirmarCotizacionWA() {
            const destinoSelect = document.getElementById('cot-destino');
            const destinoTexto = destinoSelect.options[destinoSelect.selectedIndex].text;
            const numPersonas = document.getElementById('cot-num').value;
            const total = document.getElementById('cot-total').innerText;

            const mensaje = `Hola AURAX GT, deseo solicitar una cotización privada:%0A- Destino: ${destinoTexto}%0A- Personas: ${numPersonas}%0A- Total Estimado: ${total}`;
            window.open(`https://wa.me/50254342015?text=${mensaje}`, '_blank');
        }
    </script>
</body>
</html>
