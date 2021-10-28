<template>
  <div class="container_principal">
    <div class="stylefooter">
      <div class="ContentHistory">
        <img src="assets/images/CDGLOGO.png" style="height: 3.1rem" />
        <div class="style_svg">
          <i class="lni lni-facebook-original"></i>
          <i class="lni lni-instagram-original"></i>
          <i class="lni lni-instagram-original"></i>
        </div>
        <div class="div_1">
          <h1>
            Buscamos sempre a melhoria contínua dos nossos serviços oferecendo
            uma gestão contábil, fiscal e trabalhista de excelência, e, além de
            consultoria nessas áreas, também buscamos prestar serviços de
            qualidade através de planejamento tributário.
          </h1>
        </div>
      </div>

      <div class="style_contact">
        <div class="contato">
          <h1 id="titulo_item">Contato</h1>
          <a id="item"
            >Rua Pedro Galdino Moreira, 142 | Jardim Paulista | Monte Mor |
            SP</a
          >
          <a id="item">(19) 3879-5995</a>
          <a id="item">(19) 99317-6589</a>
          <a id="item">contato@cdgcontabilidade.com.br</a>
        </div>
        <div class="services">
          <div class="item_service">
            <h1 id="titulo_item">Serviços</h1>
            <a id="service_text">Contabilidade</a>
            <a id="service_text">Fiscal e Tributario</a>
            <a id="service_text">Administração de Pessoal</a>
            <a id="service_text">Consultoria</a>
          </div>
          <div class="item_service">
            <h1 id="titulo_item">Navegação</h1>
            <a id="service_text">Home</a>
            <a id="service_text">Nossas Soluções</a>
            <a id="service_text">Quem Somos</a>
            <a id="service_text">Contato</a>
          </div>
          <div class="item_service">
            <h1 id="titulo_item">Especilidades</h1>
            <a id="service_text">Prestadores de Serviços</a>
            <a id="service_text">Comércio</a>
            <a id="service_text">Indústia</a>
            <a id="service_text">Construção Civil</a>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="content_rodape_style">
    <div class="rodape_style">
      <h1 id="text_footer">Contabilidade em Monte Mor - SP</h1>
      <h1 id="text_footer">2021 - Todos os direitos reservados</h1>
        <a id="tag_a_dev" target="_blank" href="https://alexgenuino.github.io/"
          >Desenvolvido por Alexsander Genuino</a
        >
    </div>
  </div>
  <footer id="footer" class="footer_area">
    <div class="container">
      <div
        class="
          footer_wrapper
          text-center
          d-lg-flex
          align-items-center
          justify-content-between
        "
      >
        
        <div class="footer_social pt-15">
          <ul>
            <li>
              <a href="#"><i class="lni lni-facebook-original"></i></a>
            </li>
            <li>
              <a href="#"><i class="lni lni-instagram-original"></i></a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  //props: ['textconteudo', 'icon', 'title'],
};
</script>

<style>
:root {
  --text-size: 14px;
  --line-size-height: 28px;
}

@media (min-width: 1441px) {
    .footer_area {
      display: none;
    }
}

@media (max-width: 1440px) {
  :root {
    --text-size: 14px;
    --line-size-height: 20px;
  }
  .container_principal {
    width: 100%;
    height: 50vh;
    background: white;
    display: none;
  }
  .content_rodape_style {
    display: none;
  }
}

@media (max-width: 1025px) {
  :root {
    --text-size: 14px;
    --line-size-height: 20px;
  }
}

@media (max-width: 769px) {
  :root {
    --text-size: 14px;
    --line-size-height: 16px;
  }

  .container_principal {
    width: 100%;
    height: 50vh;
    background: white;
    display: none;
  }
}

.container_principal {
  width: 100%;
  height: 50vh;
  background: white;
}

.stylefooter {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  background: white;
}

.ContentHistory {
  width: 30%;
  height: 90%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: space-around;
  border-right: 2px solid;
  border-right-color: #bababa;
}

.StyleSVG {
  width: 1.5rem;
  height: 1.5rem;
  color: #470606;
  cursor: pointer;
}

.div_1 {
  width: 50%;
}

.div_1 h1 {
  font-family: "poppins, sans-serif";
  font-style: initial;
  font-weight: 400;
  font-size: var(--text-size);
  line-height: var(--line-size-height);
  color: #5a5872;
  text-align: center;
}

.style_contact {
  width: 90%;
  height: 90%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}

.contato {
  width: 95%;
  height: 50%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

#titulo_item {
  font-family: "poppins, sans-serif";
  font-style: normal;
  font-weight: 400;
  font-size: var(--text-size);
  line-height: var(--line-size-height);
  color: #5a5872;
  text-align: center;
  align-self: flex-start;
  padding: 1%;
}

#item {
  font-family: "poppins, sans-serif";
  font-style: initial;
  font-weight: 400;
  font-size: var(--text-size);
  line-height: var(--line-size-height);
  color: #5a5872;
  text-align: center;
  align-self: flex-start;
}

.services {
  width: 95%;
  height: 50%;
  display: flex;
  flex-direction: row;
}

.item_service {
  height: 100%;
  width: 30%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

#service_text {
  font-family: "poppins, sans-serif";
  font-style: initial;
  font-weight: 400;
  font-size: var(--text-size);
  line-height: var(--line-size-height);
  color: #5a5872;
  text-align: center;
  align-self: flex-start;
}


.rodape_style {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  background: #470606;
}

.rodape_style #text_footer {
  font-family: "poppins, sans-serif";
  font-style: initial;
  font-weight: 200;
  text-align: center;
  font-size: 12px;
  line-height: var(--line-size-height);
  color: white;
  margin-left: 15%;
  text-transform: uppercase;
}

#tag_a_dev {
  font-family: "poppins, sans-serif";
  font-style: initial;
  font-weight: 200;
  text-align: center;
  font-size: 12px;
  line-height: 55px;
  color: white;
  margin-left: 15%;
  text-transform: uppercase;
}

.style_svg {
  width: 30%;
  display: flex;
  align-items: center;
  justify-content: space-around;
}

.style_svg i {
  width: 1.5rem;
  height: 1.5rem;
  color: #470606;
  cursor: pointer;
}

.style_svg i:hover {
  color: #bababa;
}
</style>