#
<img align="right" src="https://count.getloli.com/get/@:Aurorp1g?theme=moebooru">
<!DOCTYPE html>
<html lang="es">
<head>
	<meta charset="UTF-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<title>Portafolio Juan Sanchez</title>
	<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">
	<style>
		:root{
			--bg:#05070f;
			--surface:rgba(14,16,33,0.9);
			--surface-strong:rgba(18,21,48,0.95);
			--border:rgba(124,58,237,0.35);
			--accent:#7c3aed;
			--accent2:#8b5cf6;
			--text:#e6eef8;
			--muted:#8a9db9;
		}
		*{box-sizing:border-box;}
		body{font-family:Inter, system-ui, Arial, sans-serif; margin:0; min-height:100vh; background:radial-gradient(circle at top, rgba(124,58,237,0.15), transparent 30%), linear-gradient(180deg,#04060f 0%, #070b17 100%); color:var(--text); display:flex; justify-content:center; padding:36px 20px;}
		.page{width:100%; max-width:1120px; display:grid; gap:24px;}
		.card, .about-box, .info-card, .service-card, .contact-card{background:var(--surface); border:1px solid rgba(255,255,255,0.14); clip-path:polygon(0 20px, 20px 0, 100% 0, 100% calc(100% - 20px), calc(100% - 20px) 100%, 0 100%); box-shadow:0 25px 90px rgba(0,0,0,0.45); backdrop-filter:blur(20px); position:relative; overflow:hidden;}
		.card::before, .about-box::before, .info-card::before, .service-card::before, .contact-card::before{content:''; position:absolute; top:0; left:0; width:100%; height:4px; background:linear-gradient(90deg, rgba(124,58,237,0.95), rgba(124,58,237,0.18));}
		.card::after, .about-box::after, .info-card::after, .service-card::after, .contact-card::after{content:''; position:absolute; bottom:0; right:0; width:24px; height:24px; background:rgba(124,58,237,0.12); clip-path:polygon(100% 0, 0 100%, 100% 100%);}
		.card{padding:36px; display:flex; gap:28px; align-items:center;}
		.hero-content{flex:1;}
		h1{font-family:'Bebas Neue', 'Oswald', sans-serif; font-weight:400; text-transform:uppercase; margin:0 0 16px; letter-spacing:0.08em; line-height:0.95; font-size:clamp(3rem, 7vw, 6.5rem); color:transparent; background:linear-gradient(90deg,var(--accent), var(--accent2)); -webkit-background-clip:text; background-clip:text;}
		.hero-subtitle{margin:0 0 24px; color:var(--muted); letter-spacing:0.18em; text-transform:uppercase; font-size:0.9rem;}
		.presentation{margin:0 0 22px; color:#d0daf4; font-size:1rem; line-height:1.8;}
		.about-text{margin:0 0 20px; color:#d8e2ff; line-height:1.75;}
		ul.services{display:flex; gap:14px; flex-wrap:wrap; padding:0; margin:0; list-style:none;}
		ul.services li{background:rgba(255,255,255,0.04); border:1px solid rgba(124,58,237,0.2); padding:12px 16px; border-radius:16px; color:#f0f5ff; font-weight:700; text-transform:uppercase; font-size:0.9rem; letter-spacing:0.06em;}
		.card, .about-box, .info-card, .service-card, .contact-card{background:var(--surface); border:1px solid rgba(255,255,255,0.14); border-radius:28px; box-shadow:0 25px 90px rgba(0,0,0,0.45); backdrop-filter:blur(20px); position:relative; overflow:hidden;}
		.card::before, .about-box::before, .info-card::before, .service-card::before, .contact-card::before{content:''; position:absolute; top:0; left:0; width:100%; height:4px; background:linear-gradient(90deg, rgba(124,58,237,0.95), rgba(124,58,237,0.18));}
		.about-box, .info-card, .service-card, .contact-card{padding:32px 34px;}
		.about-box{margin:0;}
		.about-box p{margin:0; color:#d8e2ff; line-height:1.85;}
		.info-grid{display:grid; grid-template-columns:repeat(2, minmax(0, 1fr)); gap:20px;}
		.info-card, .service-card, .contact-card{padding:28px 30px;}
		.info-card h3, .service-card h3, .contact-card h3{margin:0 0 14px; font-size:1.05rem; font-weight:800; letter-spacing:0.12em; text-transform:uppercase; color:#f7f9ff;}
		.info-card ul, .service-card ul, .contact-card ul{margin:0; padding-left:18px; color:#cbd5f5;}
		.info-card li, .service-card li, .contact-card li{margin-bottom:10px;}
		.service-grid{display:grid; grid-template-columns:repeat(3, minmax(0, 1fr)); gap:20px;}
		.service-card{padding:26px 28px;}
		.contact-card{margin-top:0;}
		.avatar{width:160px; min-width:160px; height:160px; border-radius:24px; background:linear-gradient(135deg,var(--accent), var(--accent2)); display:flex; align-items:center; justify-content:center; color:#071029; font-weight:800; font-size:1rem; letter-spacing:0.18em;}
		.section-title{display:flex; justify-content:space-between; align-items:center; gap:12px; margin-bottom:16px;}
		.section-title span{font-size:0.85rem; letter-spacing:0.2em; color:var(--muted); text-transform:uppercase;}
		@media(max-width:1000px){ .service-grid{grid-template-columns:1fr;} .info-grid{grid-template-columns:1fr;} }
		@media(max-width:720px){ .card{flex-direction:column; text-align:center; padding:28px 22px;} .avatar{margin:0 auto;} .hero-subtitle{font-size:0.8rem;} }
	</style>
</head>
<body>
	<div class="page">
		<main class="card" role="main">
		<div class="left">
			<h1>Graphic Designer</h1>
			<p class="presentation">Diseño experiencias digitales que combinan creatividad, estrategia y tecnología.</p>
			<p>Servicios destacados:</p>
			<ul class="services">
				<li>Logos</li>
				<li>Fotografía</li>
				<li>Contenido multimedia</li>
			</ul>
		</div>
		<div class="avatar" aria-hidden="true">JS</div>
	</main>
	<section class="about-box" aria-label="Sobre mí">
		<p>Soy Juan Diego Sánchez, diseñador gráfico y productor multimedia especializado en crear soluciones visuales modernas. Me apasiona el diseño web, el branding y la producción de contenido audiovisual. Disfruto transformar ideas en proyectos atractivos, funcionales y centrados en el usuario.</p>
	</section>
	<section class="info-grid">
		<div class="info-card">
			<h3>Estudios</h3>
			<ul>
				<li>Tecnólogo en Producción Multimedia – SENA.</li>
			</ul>
		</div>
		<div class="info-card">
			<h3>Idiomas</h3>
			<ul>
				<li>Español (Nativo)</li>
			</ul>
		</div>
	</section>
	<section class="service-grid">
		<div class="service-card">
			<h3>Diseño Gráfico</h3>
			<ul>
				<li>Logos</li>
				<li>Manual de marca</li>
				<li>Branding</li>
				<li>Papelería</li>
			</ul>
		</div>
		<div class="service-card">
			<h3>Multimedia</h3>
			<ul>
				<li>Edición de Video</li>
				<li>Motion Graphics</li>
				<li>Fotografía</li>
				<li>Retoque</li>
			</ul>
		</div>
		<div class="service-card">
			<h3>Marketing</h3>
			<ul>
				<li>Redes Sociales</li>
				<li>Banners</li>
				<li>Publicidad Digital</li>
				<li>Identidad Visual</li>
			</ul>
		</div>
	</section>
	<section class="contact-card" aria-label="Información de contacto">
		<h3>Información de contacto</h3>
		<ul>
			<li><strong>Correo electrónico:</strong> juandiegosanchezgarcia37@gmail.com</li>
			<li><strong>Teléfono:</strong> 3054590981</li>
			<li><strong>Ciudad y país:</strong> Melgar, Tolima</li>
			<li><strong>GitHub:</strong> juan</li>
			<li><strong>Instagram profesional:</strong> Juan Sanchez | Contenido Digital</li>
		</ul>
	</section>
	</div>
</body>
</html>
