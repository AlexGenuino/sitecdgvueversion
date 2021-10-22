<template>
    <section id="home" class="header_area">
    <div id="header_navbar" class="header_navbar">
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <nav class="navbar navbar-expand-lg">
              <a class="navbar-brand" href="#">
                <img id="logo" src="assets/images/CDG.png" alt="Logo" />
              </a>
              <button
                class="navbar-toggler"
                type="button"
                data-toggle="collapse"
                data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent"
                aria-expanded="false"
                aria-label="Toggle navigation"
              >
                <span class="toggler-icon"></span>
                <span class="toggler-icon"></span>
                <span class="toggler-icon"></span>
              </button>
              <div
                class="collapse navbar-collapse sub-menu-bar"
                id="navbarSupportedContent"
              >
                
                <ul id="nav" class="navbar-nav ml-auto">
                  <li class="nav-item">
                    <a class="page-scroll active" href="#home">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="page-scroll" href="#about">Quem Somos</a>
                  </li>
                  <li class="nav-item">
                    <a class="page-scroll" href="#services">Nossas Soluções</a>
                  </li>
                  <li class="nav-item">
                    <a class="page-scroll" href="#contact">Contato</a>
                  </li>
                </ul>
              </div>
            </nav>
          </div>
        </div>
      </div>
    </div>
    <div class="header_hero">
      <div
        class="single_hero bg_cover d-flex align-items-center"
        style="background-image: url(assets/images/hero.jpg)"
      >
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-lg-8 col-md-10">
              <div class="hero_content text-center">
                <h2
                  class="hero_title wow fadeInUp"
                  data-wow-duration="1.3s"
                  data-wow-delay="0.2s"
                >
                  Somos um escritório de Contabilidade<br />
                </h2>
                <p
                  class="wow fadeInUp"
                  data-wow-duration="1.3s"
                  data-wow-delay="0.5s"
                >
                  As melhores soluções para sua empresa, serviço ou comércio.
                  Conte conosco!
                </p>
                <a
                  href="#features"
                  class="main-btn wow fadeInUp"
                  data-wow-duration="1.3s"
                  data-wow-delay="0.8s"
                  >Faça um orçamento</a
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  //props: ['textconteudo', 'icon', 'title'],
};
</script>

<style scoped>

</style>