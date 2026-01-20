<template>
  <div class="app min-vh-100 d-flex flex-column">
    <!-- HEADER -->
    <header class="navbar navbar-expand-lg navbar-dark header p-4 px-lg-5">
      <div class="container-fluid">
        <div class="d-flex align-items-center gap-3">
          <div class="logo-icon">
            <Logo />
          </div>

          <div class="logo">
            <span>LUIZ</span><br />
            <span class="size-min">PROJETOS E TECNOLOGIA</span><br />
            <span class="size-min">EM ENERGIA</span>
          </div>
        </div>

        <nav class="d-flex gap-4">
          <a class="nav-link text-light" href="#servicos">Serviços</a>
          <a class="nav-link text-light" href="#sobre">Sobre</a>
          <a class="nav-link text-light" href="#contato">Contato</a>
        </nav>
      </div>
    </header>

    <!-- HERO -->
    <section class="hero position-relative">
      <video
        class="hero-video"
        autoplay
        muted
        loop
        playsinline
      >
        <source src="./videos/energia.mp4" type="video/mp4" />
      </video>

      <div class="hero-overlay"></div>

      <div class="container position-relative h-100">
        <div class="row h-100 align-items-center">
          <div class="col-lg-6 text-start hero-content reveal">
            <h2 class="display-5 fw-bold mb-3">
              Projetos elétricos e soluções energéticas de alto padrão
            </h2>

            <p class="lead mb-4">
              Engenharia, tecnologia e segurança aplicadas à energia.
            </p>

            <button class="btn btn-info btn-lg rounded-pill px-5 fw-bold">
              Solicitar orçamento
            </button>
          </div>
        </div>
      </div>
    </section>

    
 <!-- SOBRE -->
<section id="sobre" class="py-5 mb-4 reveal">
  <div class="container">
    <div class="row align-items-center g-5">

      <!-- TEXTO -->
      <div class="col-lg-6 text-start">
        <h2 class="mb-3 size-min">SOBRE MIM</h2>

        <p class="about-text">
          Sou Luiz, atuo com projetos elétricos e soluções técnicas em energia,
          sempre com foco em segurança, eficiência e conformidade com as normas.
        </p>

        <p class="about-text mt-3">
          Trabalho no desenvolvimento de projetos elétricos para diferentes tipos
          de instalações, buscando soluções bem dimensionadas, confiáveis e alinhadas
          às necessidades de cada cliente.
        </p>
      </div>

      <!-- FOTO -->
      <div class="col-lg-6">
        <div class="about-image">
          <img
            src="../public/images/luiz.png"
            alt="Luiz - Projetista Elétrico"
          />
        </div>
      </div>

    </div>
  </div>
</section>


   <!-- SERVIÇOS -->
<section id="servicos" class="py-5 reveal" style="background: var(--bg);">
  <div class="container">
    <h2 class="text-center mb-5 text-light size-medium">SERVIÇOS</h2>

    <div class="row g-4">

      <div class="col-md-4">
        <div class="card service-card h-100 reveal">
          <img src="../public/images/projeto.jpg" alt="Projetos Elétricos" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">Projetos Elétricos</h5>
            <p class="card-text">
              Desenvolvimento completo de projetos elétricos residenciais, comerciais e industriais,
              garantindo segurança e eficiência.
            </p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card service-card h-100 reveal">
          <img src="../public/images/eficiencia.png" alt="Eficiência Energética" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">Eficiência Energética</h5>
            <p class="card-text">
              Soluções para otimizar consumo de energia, reduzir custos e aumentar a sustentabilidade das instalações.
            </p>
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="card service-card h-100 reveal">
          <img src="../public/images/consultoria.png" alt="Consultoria Técnica" class="card-img-top">
          <div class="card-body">
            <h5 class="card-title">Consultoria Técnica</h5>
            <p class="card-text">
              Orientação especializada para execução de projetos elétricos, análise de conformidade e soluções sob medida.
            </p>
          </div>
        </div>
      </div>

    </div>
  </div>
</section>

    
    <!-- STATS -->
    <section class="stats py-5 reveal">
      <div class="container">
        <div class="row text-center g-4">
          <div class="col-md-3">
            <h3 data-count="100">0</h3>
            <p>Projetos realizados</p>
          </div>
          <div class="col-md-3">
            <h3 data-count="10">0</h3>
            <p>Anos de experiência</p>
          </div>
          <div class="col-md-3">
            <h3 data-count="100">0</h3>
            <p>Conformidade técnica</p>
          </div>
          <div class="col-md-3">
            <h3 data-count="24">0</h3>
            <p>Agilidade no atendimento</p>
          </div>
        </div>
      </div>
    </section>

    <!-- CONTATO -->
    <section id="contato" class="py-5 text-center reveal">
      <div class="container">
        <h2 class="mb-4">Contato</h2>
        <button class="btn btn-outline-info btn-lg rounded-pill px-5">
          Falar no WhatsApp
        </button>
      </div>
    </section>

    <footer class="footer mt-auto py-3 text-center">
      © {{ new Date().getFullYear() }} Luiz Projetos e Tecnologia em Energia
    </footer>
  </div>
</template>

<style>
/* RESET */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* VARS */
:root {
  --bg: #020617;
  --primary: #38bdf8;
  --secondary: #22d3ee;
  --text: #e5e7eb;
}

.app {
  font-family: 'Inter', 'Segoe UI', sans-serif;
  background: var(--text);
  color: var(--text);
}

/* HEADER */
.header {
  background: var(--bg);
  backdrop-filter: none;
  transition: background 0.4s ease, backdrop-filter 0.4s ease;
}

.header.scrolled {
  background: rgba(2, 6, 23, 0.85);
  backdrop-filter: blur(10px);
}

/* LOGO */ 
.logo-icon { 
  width: 4rem; 
  height: 4rem; 
  display: flex; 
} 
.logo-icon svg { 
  width: 100%; 
  height: 100%; 
} 
.logo { 
  font-weight: bold; 
  font-size: 2rem; 
  line-height: 0.6; 
} 
.size-min { 
  font-size: 1rem; 
  letter-spacing: 2px; 
  color: var(--secondary); 
  line-height: 0.4; 
}

.size-medium { 
  font-size: 1.7rem; 
  letter-spacing: 2px; 
  color: var(--secondary); 
  line-height: 0.4; 
}

/* HERO */
.hero {
  min-height: 90vh;
  overflow: hidden;
}

.hero-video {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.hero-overlay {
  position: absolute;
  inset: 0;
  background: linear-gradient(
    90deg,
    rgba(2,6,23,.85),
    rgba(2,6,23,.6),
    rgba(2,6,23,.85)
  );
}

.hero-content {
  padding-top: 25vh;
}

/* SOBRE COM IMAGEM */
#sobre .about-text {
  max-width: 32rem;
  color: #020617;
  font-size: 1.05rem;
  line-height: 1.6;
}

.about-image {
  position: relative;
  max-width: 23rem;   
  margin-left: 6rem;
  overflow: visible;
  border-radius: 18px;
}

.about-image::before {
  content: '';
  position: absolute;
  left: -1.5rem;    
  bottom: -1.5rem;   
  width: 100%;
  height: 100%;
  background: #05183c;
  border-radius: 18px;
  z-index: -1;                  
}

/* FOTO */
.about-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 18px;
  transition: transform 0.6s ease;
}

.about-image:hover img {
  transform: scale(1.05);
}


/* MOBILE */
@media (max-width: 991px) {
  #sobre {
    text-align: center;
  }

  #sobre .about-text {
    margin: 0 auto;
  }
}

/* SERVIÇOS */
#servicos .service-card {
  background: #020617;
  border: 1px solid #1e293b;
  border-radius: 20px;
  overflow: hidden;
  transition: transform 0.4s ease, box-shadow 0.4s ease;
  cursor: pointer;
}

#servicos .service-card:hover {
  transform: translateY(-10px) scale(1.03);
  box-shadow: 0 0 40px rgba(34, 211, 238, 0.25);
}

#servicos .service-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  transition: transform 0.5s ease;
}

#servicos .service-card:hover img {
  transform: scale(1.1);
}

#servicos .card-body {
  padding: 2rem 0.5rem;
}

#servicos .card-title {
  font-size: 1.25rem;
  font-weight: bold;
  text-transform: uppercase;
  color: var(--secondary);
  margin-bottom: 0.5rem;
  text-align: center;
}

#servicos .card-text {
  font-size: 0.95rem;
  line-height: 1.5;
  color: var(--text);
  text-align: center;  
}

/* STATS */
.stats h3 {
  font-size: 2.5rem;
  color: var(--secondary);
}

/* CARDS */
.service-card {
  padding: 2.5rem;
  border-radius: 20px;
  background: #020617;
  border: 1px solid #1e293b;
  transition: transform .4s, box-shadow .4s;
}

.service-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 0 40px rgba(34,211,238,.25);
}

/* REVEAL */
.reveal {
  opacity: 0;
  transform: translateY(40px);
  transition: .8s ease;
}

.reveal.active {
  opacity: 1;
  transform: translateY(0);
}


</style>


<script setup>
import Logo from './Components/Icons/logo.vue'
import { onMounted } from 'vue'

onMounted(() => {
  /* SCROLL REVEAL */
  const revealObserver = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('active')
        revealObserver.unobserve(entry.target)
      }
    })
  }, { threshold: 0.15 })

  document.querySelectorAll('.reveal').forEach(el => revealObserver.observe(el))

  /* CONTADOR */
  const animateCounter = el => {
    const target = +el.dataset.count
    let current = 0
    const increment = target / 60

    const update = () => {
      current += increment
      if (current < target) {
        el.innerText = Math.ceil(current)
        requestAnimationFrame(update)
      } else {
        el.innerText = "+" + target
      }
    }

    update()
  }

  const statsSection = document.querySelector('.stats')
  if (statsSection) {
    const statsObserver = new IntersectionObserver(entries => {
      if (entries[0].isIntersecting) {
        statsSection.querySelectorAll('[data-count]').forEach(animateCounter)
        statsObserver.disconnect()
      }
    }, { threshold: 0.3 })

    statsObserver.observe(statsSection)
  }

  /* HEADER SCROLL */
  const header = document.querySelector('.header')
  window.addEventListener('scroll', () => {
    header.classList.toggle('scrolled', window.scrollY > 80)
  })

  /* VIDEO MOBILE */
  const video = document.querySelector('.hero-video')
  if (video && window.innerWidth < 768) {
    video.pause()
    video.removeAttribute('autoplay')
  }
})
</script>