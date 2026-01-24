<template>
  <div class="app min-vh-100 d-flex flex-column">
    <!-- HEADER -->
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
          <a class="nav-link nav-underline text-light p-1" href="#faq"
            >Dúvidas</a
          >
          <a class="nav-link nav-underline text-light p-1" href="#contato"
            >Contato</a
          >
          <a class="nav-link nav-orcamento p-1 px-3" href="#contato"
            >Orçamento</a
          >
        </nav>
      </div>
    </header>

    <!-- HERO -->
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
              <a href="#contato" class="btn btn-info btn-lg rounded-pill px-5 fw-bold">
                Solicitar orçamento
              </a>
              <a href="#servicos" class="btn bg-white btn-lg rounded-pill px-5 fw-bold">
                Conhecer serviços
              </a>
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
        <h2 class="fs-6 size-min text-center mb-4">SERVIÇOS</h2>

        <h2 class="service-desc fw-bold">
          Soluções completas em <span class="">engenharia elétrica</span>
        </h2>

        <p class="service-p">
          Oferecemos uma gama completa de serviços para atender todas as suas
          necessidades em projetos elétricos e energia solar.
        </p>

        <div class="row g-4">
          <div class="col-md-4">
            <div class="service-card h-100 p-4">
              <div class="service-icon"><House /></div>
              <h5 class="fw-bold text-black">Projetos Residenciais</h5>
              <p>
                Projetos elétricos completos para residências, incluindo
                dimensionamento, quadros de distribuição e iluminação.
              </p>
              <ul class="service-list">
                <li>
                  <span class="list-icon"></span>
                  Entrada de energia
                </li>
                <li>
                  <span class="list-icon"></span>
                  Quadro de distribuição
                </li>
                <li>
                  <span class="list-icon"></span>
                  Iluminação
                </li>
                <li>
                  <span class="list-icon"></span>
                  Tomadas e circuitos
                </li>
              </ul>
              <a class="service-more">Saiba mais <Arrow /></a>
            </div>
          </div>

          <div class="col-md-4">
            <div class="service-card h-100 p-4">
              <div class="service-icon"><Building /></div>
              <h5 class="fw-bold text-black">Projetos Comerciais</h5>
              <p>
                Soluções elétricas para estabelecimentos comerciais, escritórios
                e lojas com foco em eficiência.
              </p>
              <ul class="service-list">
                <li>
                  <span class="list-icon"></span>
                  Sistemas de iluminação LED
                </li>
                <li>
                  <span class="list-icon"></span>
                  Automação predial
                </li>
                <li>
                  <span class="list-icon"></span>
                  Sistemas de emergência
                </li>
                <li>
                  <span class="list-icon"></span>
                  Climatização
                </li>
              </ul>
              <a class="service-more">Saiba mais <Arrow /></a>
            </div>
          </div>

          <div class="col-md-4">
            <div class="service-card h-100 p-4">
              <div class="service-icon"><Industry /></div>
              <h5 class="fw-bold text-black">Projetos Industriais</h5>
              <p>
                Projetos elétricos industriais de baixa e média tensão,
                incluindo subestações e painéis.
              </p>
              <ul class="service-list">
                <li>
                  <span class="list-icon"></span>
                  Subestações
                </li>
                <li>
                  <span class="list-icon"></span>
                  Painéis elétricos
                </li>
                <li>
                  <span class="list-icon"></span>
                  Sistemas de força
                </li>
                <li>
                  <span class="list-icon"></span>
                  Correção fator potência
                </li>
              </ul>
              <a class="service-more">Saiba mais <Arrow /></a>
            </div>
          </div>

          <div class="col-md-4">
            <div class="service-card h-100 p-4">
              <div class="service-icon"><Sun /></div>
              <h5 class="fw-bold text-black">Energia Solar Fotovoltaica</h5>
              <p>
                Projetos completos de sistemas fotovoltaicos on-grid e off-grid
                para geração de energia limpa.
              </p>
              <ul class="service-list">
                <li>
                  <span class="list-icon"></span>
                  Dimensionamento
                </li>
                <li>
                  <span class="list-icon"></span>
                  Análise de viabilidade
                </li>
                <li>
                  <span class="list-icon"></span>
                  Homologação
                </li>
                <li>
                  <span class="list-icon"></span>
                  Monitoramento
                </li>
              </ul>
              <a class="service-more">Saiba mais <Arrow /></a>
            </div>
          </div>

          <div class="col-md-4">
            <div class="service-card h-100 p-4">
              <div class="service-icon"><Document /></div>
              <h5 class="fw-bold text-black">Laudos e Regularização</h5>
              <p>
                Elaboração de laudos técnicos, ART e regularização de
                instalações junto à concessionária.
              </p>
              <ul class="service-list">
                <li>
                  <span class="list-icon"></span>
                  Laudo de instalação
                </li>
                <li>
                  <span class="list-icon"></span>
                  ART
                </li>
                <li>
                  <span class="list-icon"></span>
                  Regularização
                </li>
                <li>
                  <span class="list-icon"></span>
                  SPDA
                </li>
              </ul>
              <a class="service-more">Saiba mais <Arrow /></a>
            </div>
          </div>

          <div class="col-md-4">
            <div class="service-card h-100 p-4">
              <div class="service-icon"><Energy /></div>
              <h5 class="fw-bold text-black">Consultoria Técnica</h5>
              <p>
                Consultoria especializada em eficiência energética e adequação
                de instalações às normas.
              </p>
              <ul class="service-list">
                <li>
                  <span class="list-icon"></span>
                  Eficiência energética
                </li>
                <li>
                  <span class="list-icon"></span>
                  Adequação NR-10
                </li>
                <li>
                  <span class="list-icon"></span>
                  Análise termográfica
                </li>
                <li>
                  <span class="list-icon"></span>
                  Treinamentos
                </li>
              </ul>
              <a class="service-more">Saiba mais <Arrow /></a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- FAQ -->
    <section id="faq" class="py-5 reveal">
      <div class="container">
        <p class="fs-6 fw-medium size-min text-center">PERGUNTAS FREQUENTES</p>
        <h2 class="text-center mb-3 fw-bold text-black faq-title">
          Dúvidas <span class="color-primary">comuns</span>
        </h2>

        <p class="text-center color-text faq-desc">
          Aqui estão as respostas para as perguntas mais frequentes sobre
          projetos elétricos e energia solar.
        </p>

        <div class="faq-item" v-for="(faq, i) in faqs" :key="i">
          <button class="faq-question" @click="toggleFaq(i)">
            <!-- coluna 1 -->
            <div class="faq-icon">
              <Help />
            </div>

            <!-- coluna 2 -->
            <div class="faq-content">
              <span class="faq-text">{{ faq.q }}</span>
            </div>

            <!-- coluna 3 -->
            <div class="faq-arrow-wrapper">
              <ArrowSimple
                class="faq-arrow"
                :class="{ open: activeFaq === i }"
              />
            </div>
          </button>

          <div class="faq-answer-wrapper" :class="{ open: activeFaq === i }">
            <div class="faq-answer">
              {{ faq.a }}
            </div>
          </div>
        </div>

        <div class="faq-duvida text-center mt-5">
          <h5>Não encontrou sua dúvida?</h5>
          <p>Entre em contato e terei prazer em responder suas perguntas</p>
          <a href="#contato">Falar com Luiz</a>
        </div>
      </div>
    </section>
  </div>

  <!-- CONTATO -->
  <section id="contato" class="py-5 reveal contato-bg">
    <div class="container">
      <h3 class="fs-6 size-min text-center mb-3">CONTATO</h3>
      <h1 class="text-center mb-3 fw-bold text-white faq-title">
        Vamos conversar sobre seu <span class="color-primary">projeto?</span>
      </h1>
      <p class="text-center faq-desc color-grey">
        Entre em contato para solicitar um orçamento ou tirar suas dúvidas.
        Responderei o mais breve possível.
      </p>
      <div class="row g-5 align-items-center">
        <div class="col-lg-6">
          <div class="contact-info">
            <span class="contact-icon"><Phone /></span>
            <div>
              <span>Telefone</span>
              <span>(69) 9327-1539</span>
            </div>
          </div>

          <div class="contact-info">
            <span class="contact-icon"><Email /></span>
            <div>
              <span>Email</span>
              <span>luizflavio.88@gmail.com</span>
            </div>
          </div>

          <div class="contact-info">
            <span class="contact-icon"><Locate /></span>
            <div>
              <span>Localização</span>
              <span>Porto Velho - RO</span>
            </div>
          </div>

          <div class="contact-info">
            <span class="contact-icon"><Clock /></span>
            <div>
              <span>Horário</span>
              <span>Seg-Sex: 8h às 18h</span>
            </div>
          </div>

          <hr />
          <p class="contact-media">Redes Sociais</p>
          <div class="social-links d-flex gap-3">
            <a href="https://www.facebook.com/luiz.fl.5" class="contact-social"><Facebook /></a>
            <a href="https://www.linkedin.com/in/luiz-flavio-tecn%C3%B3logo/" class="contact-social"><LinkedIn /></a>
            <a href="https://www.instagram.com/luizflavio_fl/" class="contact-social"><Instagram /></a>
          </div>
        </div>

        <div class="col-lg-6 form-container">
          <form class="contact-form">
            <div class="row">
              <div class="col-md-6">
                <label>Nome Completo</label>
                <input
                  type="text"
                  placeholder="Seu nome completo"
                  required
                  class="form-control border border-secondary text-white"
                />
              </div>
              <div class="col-md-6">
                <label>Email</label>
                <input
                  type="email"
                  placeholder="seu@email.com"
                  required
                  class="form-control border border-secondary"
                />
              </div>
            </div>

            <div class="row">
              <div class="col-md-6">
                <label>Telefone</label>
                <input
                  type="tel"
                  placeholder="(11) 99999-9999"
                  class="form-control border border-secondary"
                />
              </div>
              <div class="col-md-6">
                <label>Serviço</label>
                <select required class="form-select border border-secondary">
                  <option value="">Selecione o serviço</option>
                  <option>Projeto Industrial</option>
                  <option>Projeto Comercial</option>
                  <option>Projeto Residencial</option>
                  <option>Energia Solar</option>
                  <option>
                    Instalação de Carregadores para Carro Elétrico
                  </option>
                  <option>Laudos e Regularização</option>
                  <option>Consultoria</option>
                </select>
              </div>
            </div>

            <div>
              <label>Mensagem</label>
              <textarea
                placeholder="Descreva seu projeto ou dúvida..."
                rows="4"
                class="form-control border border-secondary"
              ></textarea>
            </div>

            <button type="submit" class="btn-submit">
              <Airplane /> Enviar Mensagem
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="footer py-4">
    <hr />
    <div
      class="container d-flex justify-content-between align-items-center pt-3"
    >
      <div class="d-flex gap-2">
        <div class="logo-icon">
          <Logo />
        </div>
        <div class="logo pt-1">
          <span>LUIZ</span><br />
          <span class="size-min">PROJETOS E TECNOLOGIA</span><br />
          <span class="size-min">EM ENERGIA</span>
        </div>
      </div>
      <span>Desenvolvido por <a href="https://anamaria-portfolio.netlify.app/">Ana M Souza</a></span>
      <span>CREA: XXXXX</span>
    </div>
  </footer>
</template>

<style>
:root {
  --bg: #020617;
  --primary: #0ea5e9;
  --secondary: #22d3ee;
  --text: #e5e7eb;
}

.app {
  font-family: Inter, sans-serif;
}

.color-primary {
  color: var(--primary);
}

.color-text {
  color: #475569;
}

.color-grey {
  color: #94a3b8;
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
  font-family: sans-serif;
}

.service-desc {
  text-align: center;
  font-size: 3rem;
  margin-bottom: 2.5rem;
  color: #0f172a;
}

.service-desc span {
  color: var(--primary);
}

.service-p {
  text-align: center;
  font-size: 1.2rem;
  margin-bottom: 3rem;
  color: #475569;
  padding: 0 20%;
}

.service-card {
  background: #fefefe;
  color: #334155;
  padding: 2rem;
  border-radius: 20px;
  transition: 0.4s;
}

.service-card:hover {
  box-shadow: 0 0 40px rgba(0, 0, 0, 0.08);
}

.service-icon {
  width: 3.5rem;
  height: 3.5rem;
  padding: 1rem;
  background: rgba(56, 189, 248, 0.1);
  color: var(--primary);
  border-radius: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 1rem;
  transition:
    background 0.3s ease,
    color 0.3s ease;
}

.service-icon svg {
  width: 100%;
  height: 100%;
  transition:
    fill 0.3s ease,
    stroke 0.3s ease;
}

.service-card:hover .service-icon {
  background: var(--primary);
  color: #fff;
}

.service-card:hover .service-icon svg {
  fill: currentColor;
  stroke: currentColor;
}

.service-list {
  list-style: none;
  padding: 0;
  color: #334155;
}
.service-list li {
  display: flex;
  align-items: center;
  gap: 0.8rem;
  margin-bottom: 0.3rem;
  letter-spacing: 0.05rem;
  font-size: 0.8rem;
  color: #6b7280;
}

.service-list .list-icon {
  width: 6px;
  height: 6px;
  background: var(--primary);
  border-radius: 50%;
}

.service-more {
  display: inline-block;
  margin-top: 0.5rem;
  color: var(--primary);
  font-weight: 500;
  cursor: pointer;
  text-decoration: none;
}

.service-more svg {
  width: 0.7rem;
  height: 0.7rem;
  margin-left: 0.3rem;
  margin-bottom: 0.2rem;
  rotate: 180deg;
  transition: transform 0.3s ease; /* transição no SVG */
}

/* hover no link, movimento só no SVG */
.service-more:hover svg {
  transform: translateX(-5px);
}

/* FAQ */
.faq-title {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.faq-desc {
  font-size: 1.1rem;
  margin-bottom: 2rem;
  padding: 0 23%;
}

.faq-item {
  border: 2px solid #e5e7eb;
  border-radius: 1rem;
  font-size: 1.2rem;
  padding: 1rem 1.5rem;
  margin-bottom: 1rem;
}

.faq-icon {
  background: #f1f5f9;
  border-radius: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  padding: 0.7rem;

  transition:
    background 0.3s ease,
    color 0.3s ease;
}

.faq-icon svg {
  width: 1.3rem;
  height: 1.3rem;
  color: #8e9dab;
  transition: color 0.3s ease;
}

.faq-question {
  width: 100%;
  background: none;
  border: none;
  padding: 1rem 0;
  font-weight: 600;
  cursor: pointer;

  display: grid;
  grid-template-columns: auto 1fr auto;
  align-items: center;
  justify-content: center;
  column-gap: 1rem;
}

.faq-arrow {
  width: 1.2rem;
  height: 1.2rem;
  transition: transform 0.35s ease;
  color: #64748b;
}

.faq-content {
  text-align: left;
}

.faq-text {
  font-size: 1.1rem;
  color: #0f172a;
  transition: color 0.3s ease;
}

/* quando aberto */
.faq-arrow.open {
  transform: rotate(180deg);
}
.faq-arrow-wrapper {
  display: flex;
  align-items: center;
  justify-content: center;
}

.faq-answer-wrapper {
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.4s ease;
}

.faq-answer-wrapper.open {
  max-height: 10rem;
}

.faq-answer {
  padding: 0 0 1rem 4.8rem;
  color: #4b5563;
  line-height: 1.6;
  font-size: 1rem;
}

.faq-question {
  transition: color 0.3s ease;
}

.faq-item {
  transition: border-color 0.3s ease;
}

.faq-item:has(.faq-answer-wrapper.open) {
  border-color: var(--primary);
}

/* FAQ aberto — estado ativo */
.faq-item:has(.faq-answer-wrapper.open) .faq-icon {
  background: rgba(56, 189, 248, 0.15);
}

.faq-item:has(.faq-answer-wrapper.open) .faq-icon svg {
  color: var(--primary);
}

.faq-item:has(.faq-answer-wrapper.open) .faq-text {
  color: var(--primary);
}

.faq-duvida {
  background-color: #0ea5e91a;
  border: 0.5px solid #0ea5e92a;
  border-radius: 1rem;
  padding: 1.5rem;
}

.faq-duvida h5 {
  font-weight: bold;
}

.faq-duvida p {
  color: #475569;
  font-size: 1rem;
}

.faq-duvida a {
  color: #fff;
  font-weight: 600;
  text-decoration: none;
  background-color: #388df8;
  padding: 0.5rem 1rem;
  border-radius: 2rem;
}

.faq-duvida a {
  padding: 0.75rem 1.5rem; /* px-6 py-3 */
  background-color: #38bdf8; /* bg-sky-400 */
  color: #ffffff;
  font-weight: 600;
  border: none;
  border-radius: 9999px; /* rounded-full */
  cursor: pointer;

  transition:
    background-color 0.3s ease,
    box-shadow 0.3s ease,
    transform 0.3s ease;
}

.faq-duvida a:hover {
  background-color: #0ea5e9; /* hover:bg-sky-500 */
  box-shadow: 0 10px 25px rgba(56, 189, 248, 0.25); /* hover:shadow-lg */
  transform: translateY(-1px); /* sensação de elevação */
}

/* CONTATO */
.contato-bg {
  background: #020617;
  color: #fff;
}

.contact-info {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin-bottom: 1.5rem;
  font-size: 1.1rem;
}

.contact-icon {
  background: #38bdf81a;
  border-radius: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  padding: 1rem;

  transition:
    background 0.3s ease,
    color 0.3s ease;
}

.contact-icon svg {
  width: 1.3rem;
  height: 1.3rem;
  color: var(--primary);
  transition: color 0.3s ease;
}

.contact-info div {
  display: flex;
  flex-direction: column;
}

.contact-info div span:first-child {
  font-weight: normal;
  font-size: 0.87rem;
  color: #6b7280;
}

.contact-info div span:last-child {
  font-weight: bold;
  margin-bottom: 0.3rem;
}

.contact-media {
  font-size: 1rem;
  margin-top: 1.5rem;
  margin-bottom: 1rem;
  color: #64748b;
}

.contact-social {
  background: #1e293b;
  border-radius: 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  padding: 1rem;

  transition:
    background 0.3s ease,
    color 0.3s ease;
}

.contact-social svg {
  width: 1.3rem;
  height: 1.3rem;
  color: #94a3b8;
  transition: color 0.3s ease;
}

.form-container {
  background-color: rgba(15, 23, 42, 0.5);
  padding: 30px;
  border: 1px solid #1e293b;
  border-radius: 15px;
}

.contact-form label {
  color: #cbd5e1;
  font-size: 0.87rem;
  font-weight: 500;
  margin-bottom: 5px;
  display: block;
}

.contact-form input,
.contact-form select,
.contact-form textarea {
  width: 100%;
  padding: 10px 14px;
  border-radius: 8px;
  margin-bottom: 15px;
  font-size: 14px;
  background: #1e293b;
  color: #94a3b8;
}

.contact-form input::placeholder,
.contact-form select::placeholder,
.contact-form textarea::placeholder {
  color: #94a3b8;
}

.contact-form input:focus,
.contact-form select:focus,
.contact-form textarea:focus {
  outline: none;
  box-shadow: 0 0 0 2px #4da3ff;
  background: #1e293b;
}

.btn-submit {
  width: 100%;
  padding: 12px;
  background: #38bdf8;
  color: #020617;
  border: none;
  border-radius: 1rem;
  font-weight: 700;
  font-size: 1.2rem;
  cursor: pointer;
  transition: 0.3s;
}

.btn-submit svg {
  width: 1.2rem;
  height: 1.2rem;
  margin-right: 0.5rem;
  vertical-align: middle;
}

.btn-submit:hover {
  background: #4da3ff;
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

.footer a {
  color: #38bdf8;
  text-decoration: none;
}
</style>

<script setup>
import Logo from './Components/Icons/logo.vue';
import Medal from './Components/Icons/medal.vue';
import Hat from './Components/Icons/hat.vue';
import Work from './Components/Icons/work.vue';
import House from './Components/Icons/house.vue';
import Arrow from './Components/Icons/Arrows/arrow.vue';
import ArrowSimple from './Components/Icons/Arrows/arrow-simple.vue';
import Building from './Components/Icons/building.vue';
import Industry from './Components/Icons/industry.vue';
import Sun from './Components/Icons/sun.vue';
import Document from './Components/Icons/document.vue';
import Energy from './Components/Icons/energy.vue';
import Help from './Components/Icons/help.vue';
import Phone from './Components/Icons/phone.vue';
import Email from './Components/Icons/email.vue';
import Locate from './Components/Icons/locate.vue';
import Clock from './Components/Icons/clock.vue';
import Facebook from './Components/Icons/Socials/facebook.vue';
import LinkedIn from './Components/Icons/Socials/linkedin.vue';
import Instagram from './Components/Icons/Socials/instagram.vue';
import { onMounted, ref } from 'vue';
import Airplane from './Components/Icons/airplane.vue';

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
    a: 'O prazo varia de acordo com a complexidade do projeto. Para projetos residenciais, geralmente leva de 7 a 15 dias. Projetos comerciais entre 15 a 30 dias, e projetos industriais podem levar de 30 a 60 dias. Esses prazos incluem visita técnica, desenvolvimento e revisões.',
  },
  {
    q: 'Quais informações são necessárias para iniciar um projeto elétrico?',
    a: 'Para iniciar um projeto elétrico, são necessárias informações como plantas arquitetônicas, especificações de carga elétrica, requisitos de iluminação, localização do imóvel, normas técnicas aplicáveis e qualquer necessidade especial do cliente. Uma visita técnica também pode ser necessária para levantamento de dados.',
  },
  {
    q: 'Vocês oferecem suporte para aprovação do projeto junto à concessionária?',
    a: 'Sim, oferecemos suporte completo para aprovação do projeto junto à concessionária de energia. Isso inclui a preparação e envio da documentação necessária, acompanhamento do processo de aprovação e comunicação com a concessionária para garantir que todas as exigências sejam atendidas.',
  },
  {
    q: 'Quais são os benefícios de investir em energia solar fotovoltaica?',
    a: 'Investir em energia solar fotovoltaica traz diversos benefícios, como redução significativa na conta de energia elétrica, retorno sobre o investimento a médio e longo prazo, valorização do imóvel, contribuição para a sustentabilidade ambiental e independência energética. Além disso, sistemas solares podem ser elegíveis para incentivos fiscais e linhas de financiamento específicas.',
  },
  {
    q: 'É possível fazer projeto de energia solar para qualquer tipo de imóvel?',
    a: 'Sim! Desenvolvemos projetos fotovoltaicos para residências, comércios, indústrias e áreas rurais. Fazemos uma análise de viabilidade técnica e econômica para cada caso, considerando área disponível, consumo energético e orientação do telhado.',
  },
  {
    q: 'Vocês fazem também a execução da obra ou apenas o projeto?',
    a: 'Focamos no desenvolvimento de projetos elétricos de alta qualidade. No entanto, posso indicar profissionais de confiança para executar a instalação seguindo rigorosamente o projeto desenvolvido. Também ofereço acompanhamento técnico durante a execução.',
  },
  {
    q: 'Quais normas técnicas vocês seguem nos projetos elétricos?',
    a: 'Nossos projetos seguem rigorosamente as normas técnicas brasileiras, incluindo a NBR 5410 para instalações elétricas de baixa tensão, NBR 14039 para média tensão, e outras normas específicas conforme o tipo de instalação. Garantimos que todos os projetos estejam em conformidade com as regulamentações vigentes para segurança e eficiência.',
  },
  {
    q: 'Como funciona o orçamento? É gratuito?',
    a: 'Sim, a primeira consulta e orçamento são totalmente gratuitos! Após entender suas necessidades, apresento uma proposta detalhada com escopo, prazos e valores. O projeto só é iniciado após sua aprovação formal.',
  },
];

const toggleFaq = (i) => {
  activeFaq.value = activeFaq.value === i ? null : i;
};
</script>
