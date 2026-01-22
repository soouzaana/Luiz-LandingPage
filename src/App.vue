<template>
  <div class="app min-vh-100 d-flex flex-column">
    <!-- HEADER (SEM ALTERAR CORES/TAMANHO) -->
    <header class="navbar navbar-expand-lg navbar-dark header p-3 px-lg-5">
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
          <a class="nav-link nav-underline text-light p-1" href="#inicio"
            >Início</a
          >
          <a class="nav-link nav-underline text-light p-1" href="#sobre"
            >Sobre</a
          >
          <a class="nav-link nav-underline text-light p-1" href="#servicos"
            >Serviços</a
          >
          <a class="nav-link nav-underline text-light p-1" href="#portfolio"
            >Portfólio</a
          >
          <a class="nav-link nav-underline text-light p-1" href="#contato"
            >Contato</a
          >
          <a class="nav-link nav-orcamento p-1 px-3" href="#orcamento"
            >Orçamento</a
          >
        </nav>
      </div>
    </header>

    <!-- HERO (INALTERADO VISUALMENTE) -->
    <section id="inicio" class="hero position-relative">
      <video class="hero-video" autoplay muted loop playsinline>
        <source src="./videos/energia.mp4" type="video/mp4" />
      </video>
      <div class="hero-overlay"></div>

      <div class="container position-relative h-100">
        <div class="row h-100 align-items-center">
          <div class="col-lg-6 hero-content reveal text-gray">
            <h2 class="display-5 fw-bold mb-3">
              Projetos elétricos e soluções energéticas de alto padrão
            </h2>
            <p class="lead mb-4">
              Especialista em projetos elétricos residenciais, comerciais e
              industriais, com expertise em sistemas de energia solar
              fotovoltaica.
            </p>

            <div class="d-flex gap-3">
              <button class="btn btn-info btn-lg rounded-pill px-5 fw-bold">
                Solicitar orçamento
              </button>
              <button class="btn bg-white btn-lg rounded-pill px-5 fw-bold">
                Conhecer serviços
              </button>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- SOBRE -->
    <section id="sobre" class="py-5 reveal">
      <div class="container">
        <div class="row align-items-center g-5">
          <!-- FOTO -->
          <div class="col-lg-5 position-relative">
            <img src="../public/images/luiz.png" class="about-photo" />

            <!-- CARD À DIREITA -->
            <div class="exp-card right col-md-6">
              <div class="exp-card-content">
                <div class="exp-card-icon"><Medal /></div>
                <div class="d-flex row px-2">
                  <strong class="text-start">10+</strong>
                  <span>Anos de experiência</span>
                </div>
              </div>
            </div>
          </div>

          <!-- TEXTO -->
          <div class="col-lg-7">
            <h2 class="fs-6 fw-bold size-min">SOBRE MIM</h2>

            <!-- DESCRIÇÃO -->
            <p class="mb-4 description">
              Sou Luiz, engenheiro elétrico com mais de 10 anos de experiência
              em projetos elétricos residenciais, comerciais e industriais.
              Especializado em sistemas de energia solar fotovoltaica, ofereço
              soluções inovadoras e sustentáveis para otimizar o consumo
              energético dos meus clientes. Minha abordagem combina conhecimento
              técnico com atenção aos detalhes, garantindo eficiência, segurança
              e conformidade com as normas vigentes. Estou comprometido em
              entregar projetos de alta qualidade que atendam às necessidades
              específicas de cada cliente.
            </p>

            <!-- LISTA -->
            <ul class="about-list">
              <li>
                <span class="list-icon"></span>
                Engenharia Elétrica – CREA Ativo
              </li>
              <li>
                <span class="list-icon"></span>
                Especialização em Energia Solar Fotovoltaica
              </li>
              <li>
                <span class="list-icon"></span>
                Certificação em Projetos de Média Tensão
              </li>
              <li>
                <span class="list-icon"></span>
                NR-10 e NR-35 Atualizadas
              </li>
            </ul>

            <!-- BADGES -->
            <div class="row g-3 mt-4">
              <div class="col-md-6">
                <div class="info-badge">
                  <div class="icon">
                    <div class="badge-icon"><Hat /></div>
                  </div>
                  <div>
                    <strong>Formação</strong>
                    <p>Engenharia Elétrica</p>
                  </div>
                </div>
              </div>

              <div class="col-md-6">
                <div class="info-badge">
                  <div class="icon">
                    <div class="badge-icon"><Work /></div>
                  </div>
                  <div>
                    <strong>CREA Ativo</strong>
                    <p>Registro profissional regular</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <hr style="height: 1px" />

          <!-- ESTATÍSTICAS -->
          <div class="row text-center mt-2 g-4 stats">
            <div class="col-md-3">
              <strong>10+</strong>
              <p>Anos de experiência</p>
            </div>
            <div class="col-md-3">
              <strong>200+</strong>
              <p>Projetos realizados</p>
            </div>
            <div class="col-md-3">
              <strong>150+</strong>
              <p>Clientes satisfeitos</p>
            </div>
            <div class="col-md-3">
              <strong>500kW</strong>
              <p>Energia solar instalada</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- SERVIÇOS -->
    <section id="servicos" class="py-5 reveal services-bg">
      <div class="container">
        <h2 class="text-center mb-5 size-medium">SERVIÇOS</h2>

        <div class="row g-4">
          <div class="col-md-4">
            <div class="service-card h-100">
              <h5>Projetos Elétricos</h5>
              <p>Projetos completos residenciais, comerciais e industriais.</p>
              <ul>
                <li>Dimensionamento</li>
                <li>Normas técnicas</li>
                <li>Documentação</li>
              </ul>
              <a class="btn btn-outline-info rounded-pill">Saiba mais</a>
            </div>
          </div>

          <div class="col-md-4">
            <div class="service-card h-100">
              <h5>Eficiência Energética</h5>
              <p>Redução de custos e otimização energética.</p>
              <ul>
                <li>Análise de consumo</li>
                <li>Correções técnicas</li>
                <li>Sustentabilidade</li>
              </ul>
              <a class="btn btn-outline-info rounded-pill">Saiba mais</a>
            </div>
          </div>

          <div class="col-md-4">
            <div class="service-card h-100">
              <h5>Consultoria Técnica</h5>
              <p>Acompanhamento e orientação especializada.</p>
              <ul>
                <li>Execução</li>
                <li>Vistorias</li>
                <li>Laudos</li>
              </ul>
              <a class="btn btn-outline-info rounded-pill">Saiba mais</a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section class="py-5 reveal">
      <div class="container">
        <h2 class="text-center mb-5 size-medium">PERGUNTAS FREQUENTES</h2>

        <div class="faq-item" v-for="(faq, i) in faqs" :key="i">
          <button class="faq-question" @click="toggleFaq(i)">
            {{ faq.q }}
            <span>{{ activeFaq === i ? '−' : '+' }}</span>
          </button>

          <div class="faq-answer" v-show="activeFaq === i">
            {{ faq.a }}
          </div>
        </div>

        <p class="text-center mt-5">
          Não encontrou sua dúvida?
          <a href="#contato" class="text-info fw-bold">Entre em contato</a>
        </p>
      </div>
    </section>
  </div>

  <!-- CONTATO -->
  <section id="contato" class="py-5 reveal contato-bg">
    <div class="container">
      <div class="row g-5 align-items-center">
        <div class="col-lg-6">
          <h3>Contato</h3>
          <p>📞 (xx) xxxx-xxxx</p>
          <p>📧 email@email.com</p>
          <p>📍 Sua cidade - UF</p>
          <p>⏰ Seg à Sex - 08h às 18h</p>
        </div>

        <div class="col-lg-6">
          <form class="contact-form">
            <input type="text" placeholder="Nome" />
            <input type="email" placeholder="Email" />
            <textarea placeholder="Mensagem"></textarea>
            <button class="btn btn-info rounded-pill fw-bold">
              Enviar mensagem
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="footer py-4">
    <div class="container d-flex justify-content-between align-items-center">
      <Logo />
      <span>Desenvolvido por Ana M Souza</span>
      <span>CREA: XXXXX</span>
    </div>
  </footer>
</template>

<style>
:root {
  --bg: #020617;
  --primary: #38bdf8;
  --secondary: #22d3ee;
  --text: #e5e7eb;
}

.app {
  font-family: Inter, sans-serif;
}

/* HEADER */
.header {
  background: var(--bg);
  backdrop-filter: none;
  transition:
    background 0.4s ease,
    backdrop-filter 0.4s ease;
}

.header.scrolled {
  background: rgba(2, 6, 23, 0.85);
  backdrop-filter: blur(10px);
}

/* HEADER UNDERLINE */
.logo-icon {
  width: 2.5rem;
  height: 2.5rem;
  display: flex;
}

.logo-icon svg {
  width: 100%;
  height: 100%;
  color: var(--primary);
}

.logo {
  font-weight: bold;
  font-size: 1.2rem;
  letter-spacing: 0.8px;
  line-height: 0.6;
  color: var(--text);
}

.size-min {
  font-size: 0.7rem;
  letter-spacing: 0.7px;
  color: var(--secondary);
}

.size-medium {
  font-size: 1.7rem;
  letter-spacing: 2px;
  color: var(--secondary);
  line-height: 0.4;
}

.nav-underline {
  position: relative;
}

.nav-underline::after {
  content: '';
  position: absolute;
  left: 0;
  bottom: -5px;
  width: 0;
  height: 2px;
  background: var(--secondary);
  transition: 0.3s;
}

.nav-underline:hover::after {
  width: 100%;
}

.nav-orcamento {
  background-color: var(--secondary) !important;
  border-radius: 1rem;
  font-weight: bold !important;
}

.nav-orcamento:hover {
  transform: scale(1.06);
  transition: 0.3s;
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
  background: rgba(2, 6, 23, 0.8);
}

.hero-content {
  padding-top: 25vh;
  color: var(--text);
}

/* BOTÕES */
.btn-info:hover {
  transform: scale(1.06);
  transition: 0.3s;
}
.btn.bg-white:hover {
  color: var(--primary);
  transition: 0.3s;
}

/* SOBRE */
#sobre {
  color: #475569;
}

.about-photo {
  width: 80%;
  border-radius: 18px;
}

.exp-card.right {
  position: absolute;
  bottom: -1rem;
  right: 3rem;
  background: #fff;
  border-radius: 14px;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
  max-width: 15rem;
}

.exp-card-content {
  display: flex;
  gap: 1rem;
  padding: 1rem;
  border-radius: 0.9rem;
  align-items: center;
}

.exp-card-icon {
  background: rgba(34, 211, 238, 0.2);
  color: var(--secondary);
  width: 3.5rem;
  height: 2.5rem;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
}

.exp-card-content strong {
  font-size: 1.5rem;
  color: #020617;
}

.exp-card span {
  font-size: 0.9rem;
  color: #6b7280;
}

.description {
  line-height: 1.6;
  letter-spacing: 0.02rem;
  font-size: 1.12rem;
}

/* LISTA COM ÍCONE */
.about-list {
  list-style: none;
  padding: 0;
  color: #334155;
}
.about-list li {
  display: flex;
  align-items: center;
  gap: 0.8rem;
  margin-bottom: 0.8rem;
  letter-spacing: 0.04rem;
  font-size: 1rem;
}

.list-icon {
  width: 10px;
  height: 10px;
  background: var(--secondary);
  border-radius: 50%;
}

/* BADGES */
.info-badge {
  display: flex;
  gap: 1rem;
  border-radius: 14px;
  align-items: center;
}

.info-badge p {
  margin: 0;
  font-size: 0.9rem;
  color: #6b7280;
}

.icon {
  display: flex;
  align-items: center;
  justify-content: center;
  background: #f1f5f9;
  padding: 0.5rem;
  border-radius: 0.8rem;
}

.badge-icon {
  color: var(--secondary);
  width: 1.5rem;
  height: 1.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
}

/* STATS */

.stats strong {
  font-size: 2.7rem;
  color: #0f172a;
}

.stats p {
  margin: 0;
  font-size: 1rem;
  letter-spacing: 0.04rem;
  color: #64748b;
}

/* SERVIÇOS */
.services-bg {
  background: #f3f4f6;
}

.service-card {
  background: #020617;
  color: #fff;
  padding: 2rem;
  border-radius: 20px;
  transition: 0.4s;
}

.service-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 0 40px rgba(34, 211, 238, 0.25);
}

/* FAQ */
.faq-item {
  border-bottom: 1px solid #e5e7eb;
  margin-bottom: 1rem;
}

.faq-question {
  width: 100%;
  background: none;
  border: none;
  padding: 1rem 0;
  font-weight: 600;
  display: flex;
  justify-content: space-between;
  cursor: pointer;
}

.faq-answer {
  padding-bottom: 1rem;
  color: #4b5563;
}

/* CONTATO */
.contato-bg {
  background: #020617;
  color: #fff;
}

.contact-form input,
.contact-form textarea {
  width: 100%;
  margin-bottom: 1rem;
  padding: 0.8rem;
  border-radius: 10px;
  border: none;
}

/* FOOTER */
.footer {
  background: #020617;
  color: #fff;
}
</style>

<script setup>
import Logo from './Components/Icons/logo.vue';
import Medal from './Components/Icons/medal.vue';
import Hat from './Components/Icons/hat.vue';
import Work from './Components/Icons/work.vue';
import { onMounted, ref } from 'vue';

onMounted(() => {
  /* SCROLL REVEAL */
  const revealObserver = new IntersectionObserver(
    (entries) => {
      entries.forEach((entry) => {
        if (entry.isIntersecting) {
          entry.target.classList.add('active');
          revealObserver.unobserve(entry.target);
        }
      });
    },
    { threshold: 0.15 },
  );

  document
    .querySelectorAll('.reveal')
    .forEach((el) => revealObserver.observe(el));

  /* CONTADOR */
  const animateCounter = (el) => {
    const target = +el.dataset.count;
    let current = 0;
    const increment = target / 60;

    const update = () => {
      current += increment;
      if (current < target) {
        el.innerText = Math.ceil(current);
        requestAnimationFrame(update);
      } else {
        el.innerText = '+' + target;
      }
    };

    update();
  };

  const statsSection = document.querySelector('.stats');
  if (statsSection) {
    const statsObserver = new IntersectionObserver(
      (entries) => {
        if (entries[0].isIntersecting) {
          statsSection.querySelectorAll('[data-count]').forEach(animateCounter);
          statsObserver.disconnect();
        }
      },
      { threshold: 0.3 },
    );

    statsObserver.observe(statsSection);
  }

  /* HEADER SCROLL */
  const header = document.querySelector('.header');
  window.addEventListener('scroll', () => {
    header.classList.toggle('scrolled', window.scrollY > 80);
  });

  /* VIDEO MOBILE */
  const video = document.querySelector('.hero-video');
  if (video && window.innerWidth < 768) {
    video.pause();
    video.removeAttribute('autoplay');
  }
});
const activeFaq = ref(null);

const faqs = [
  {
    q: 'Qual o prazo médio para desenvolvimento de um projeto elétrico?',
    a: 'O prazo varia conforme a complexidade. Projetos residenciais levam de 7 a 15 dias, comerciais de 15 a 30 dias e industriais de 30 a 60 dias.',
  },
];

const toggleFaq = (i) => {
  activeFaq.value = activeFaq.value === i ? null : i;
};
</script>
