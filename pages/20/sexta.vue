<template>
    <div>

        <div class='main-tree'>
            <div>
                <!--
        <h5 class='hCincoOne'><i class="fa-solid fa-yin-yang"></i> Terapias</h5>
      </div>
      <div class='homeTwo'>
        <div class='homeTwoDot' :class='{ selectTitle: aplicarAcu }'>
          <nuxt-link to="/terapias">Acupuntura Sistêmica</nuxt-link>
        </div>
        <div class='homeTwoDot' :class='{ selectTitle: aplicarCran }'>
          <nuxt-link to="/terapias">Craniopuntura</nuxt-link>
        </div>
        <div class='homeTwoDot' :class='{ selectTitle: aplicarCran }'>
          <nuxt-link to="/terapias">Auriculoterapia</nuxt-link>
        </div>
        <div class='homeTwoDot' :class='{ selectTitle: aplicarCran }'>
          <nuxt-link to="/terapias">Ventosaterapia</nuxt-link>
        </div>
        <div class='homeTwoDot' :class='{ selectTitle: aplicarCran }'>
          <nuxt-link to="/terapias">Gua Sha</nuxt-link>
        </div>
        <div class='homeTwoDot' :class='{ selectTitle: aplicarCran }'>
          <nuxt-link to="/terapias">Fórmulas Magistrias Chinesas</nuxt-link>
        </div>
      -->
                <!--
              // <div @click='acupuntura()' class='homeTwoDot' :class='{ selectTitle: aplicarAcu }'>Acupuntura Sistêmica</div>
              // <div @click='craniopuntura()' class='homeTwoDot' :class='{ selectTitle: aplicarCran }'>Craniopuntura</div>
              // <div @click='auriculo()' class='homeTwoDot' :class='{ selectTitle: aplicarAur }'>Auriculoterapia</div>
              // <div @click='ventosa()' class='homeTwoDot' :class='{ selectTitle: aplicarVen }'>Ventosaterapia</div>
              -->
            </div>
            <br>
        </div>

        <br>
        <div>
            <h5 class='hCincoTwo' style='margin-right: 10px;'><i class="fa-solid fa-angle-right"></i> Escolha um horário (você será redirecionado à página de 
                pagamento) ou clique no 'whatsapp', para marcar diretamente com o acupunturista:</h5>
        </div>
        <div class='main-l-trat'>
            <a href="http://pag.ae/7YTtYQGS5" class='dot-index'>08:00 horas</a>
            <a href="http://pag.ae/7YTtYQGS5" class='dot-index'>10:00 horas</a>
            <a href="http://pag.ae/7YTtYQGS5" class='dot-index'>11:00 horas</a>
            <a href="http://pag.ae/7YTtYQGS5" class='dot-index'>12:00 horas</a>
            <a href="http://pag.ae/7YTtYQGS5" class='dot-index'>13:00 horas</a>
            <a href="http://pag.ae/7YTtYQGS5" class='dot-index'>15:00 horas</a>
            <a href="http://pag.ae/7YTtYQGS5" class='dot-index'>16:00 horas</a>
            <a href="http://pag.ae/7YTtYQGS5" class='dot-index'>17:00 horas</a>
            <a class='dot-indexOk'>18:00 horas</a>
            <a href="http://pag.ae/7YTtYQGS5" class='dot-index'>19:00 horas</a>
            <a href="http://pag.ae/7YTtYQGS5" class='dot-index'>20:00 horas</a>
            
            <!-- 7YTtYQGS5 -->
        </div>
        <nuxt-child />
        <br>
        <!--
     <div class='hr'></div>
     -->
        <br>
        <br>
        <br>
        <br>

    </div>

</template>
<script>
export default {
    scrollToTop: true,
    transition: {
        name: 'page',
        mode: 'ease-in'
    },
    head: {
        title: 'Black Desconto | Deep Acupuntura',
        htmlAttrs: {
            lang: 'pt-br'
        },
        meta: [
            { charset: 'utf-8' },
            { name: 'viewport', content: 'width=device-width, initial-scale=1' },
            { hid: 'description', name: 'description', content: '' },
            { hid: 'keywords', name: 'description', content: 'Acupuntura' },
            { name: 'format-detection', content: 'telephone=no' },
            { name: 'msapplication-TileColor', content: 'black' },
            { name: 'theme-color', content: 'black' }
        ],
        link: [
            { rel: 'apple-touch-icon', size: '180x180', href: '/img/MyLogoBoldFundo.png' },
            { rel: 'icon', type: 'image/png', size: '32x32', href: '/img/MyLogoBoldFundo.png' },
            { rel: 'icon', type: 'image/png', size: '16x16', href: '/img/MyLogoBoldFundo.png' },
            { rel: 'apple-touch-icon', size: '180x180', href: '/img/apple-touch-icon.png' },
            { rel: 'manifest', href: '/img/site.webmanifest' },
            { rel: 'mask-icon', href: '/img/safari-pinned-tab.svg', color: 'black' }
        ]
    }
}
</script>

<style scoped>
a {
    text-decoration: none;
    color: #fff;
}

i {
    color: #fff;
    font-size: .9em;
    margin: auto;
}

code {
    font-size: 0.6em;
    padding-left: 10px;
    margin-left: 15px;
    margin-right: 60px;
    border-left: solid 5px #e23a28;
    color: #ddd;
}

.divider {
    height: 15px;
    background-color: #e23a2840;
}

.divider-ultimate {
    height: 30px;
    background-color: #fff;
}

.profile {
    background: black;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 20px 0 25px 0;
    margin-top: 20px;
}

.profile a {
    text-decoration: none;
    color: #fff;
    font-size: .9em;
}

.profile img {
    height: 70px;
    margin-left: 10px;
    padding: 0 25px 0 0;
}

.profile h1 {
    margin: 13px 0 -5px -10px;
    font-size: 1.5em;
    color: #fff;
    text-shadow: -2px 2px 5px #ffffff70,
        -2px -2px 5px #ffffff70,
        2px 2px 5px #ffffff70,
        2px -2px 5px #ffffff70;
}

.profile h1:hover {
    color: #fff;
    cursor: pointer;
    text-shadow: -2px 2px 5px #e23a28,
        -2px -2px 5px #e23a28,
        2px 2px 5px #e23a28,
        2px -2px 5px #e23a28;
}

.profile h4 {
    margin: 0 0 0 -10px;
    font-size: .9em;
    font-weight: 100;
    color: #e23a28;
}

.main-one {
    display: flex;
    justify-content: center;
    flex-direction: row;
    padding: 10px 0 15px 0;
    box-shadow: 0px 10px 15px #ffffff10;
    background: black;
}

.main-one h2 {
    text-align: center;
    margin: 13px auto -20px 0px;
    font-size: 1.5em;
    color: black;
    text-shadow: -2px 2px 5px #860d0d,
        -2px -2px 5px #860d0d,
        2px 2px 5px #860d0d,
        2px -2px 5px #860d0d;
}

.main-one h3 {
    text-align: center;
    font-size: 1.3em;
    color: black;
    text-shadow: -2px 2px 5px #ffffff50,
        -2px -2px 5px #ffffff50,
        2px 2px 5px #ffffff50,
        2px -2px 5px #ffffff50;
}

.main-one div {
    margin: 0 0 0 15px;
}

.dot-indexOk {
    transition: all .3s ease-in;
    background-color: #440f0f;
    margin: 5px 10px;
    padding: 8px;
    font-size: .6em;
    text-transform: uppercase;
    text-decoration: line-through;
    font-weight: bold;
    border-radius: 5% 4% 15%;
    border: solid .5px;
    color: rgb(213, 16, 16);
}

.main-one a i {
    font-size: 1.2em;
}

.main-one a:nth-child(1) i,
.main-one a:nth-child(2) i {
    padding-right: 3px;
    margin: 0 0 0 3px;
}

.main-one a:nth-child(2) i {
    padding-right: 4px;
    margin: 0 0 0 4px;
}

.main-one a:nth-child(3) i {
    margin: 0 0 0 3px;
    padding-right: 2px;
}

.main-one a:nth-child(4) i {
    margin: 0 0 0 5px;
    padding-right: 2px;
}

.main-one a {
    margin: 0 0 0 10px;
    color: #ddd;
}

.main-two {
    display: flex;
    justify-content: space-around;
    flex-direction: row;
    padding: 15px 0 18px 0;
    color: black;
    box-shadow: 0 5px 20px #ffffff90;
    background: black;
    color: #fff;
}

.main-two a {
    margin: 20px 0 0 0px;
    color: #fff;
    font-weight: 600;
}

.main-two i {
    color: #fff;
    font-size: 1.1em;
    font-weight: 600;
}

.main-tree {
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
    margin: 0px 0 0 0;
    color: #fff;
    background: black;
    overflow-x: auto;
}

.main-tree i {
    font-size: 1.2em;
    color: #fff;
}

.main-tree h5 {
    margin-left: 10px;
}

.hCincoOne {
    margin: 10px 0px 22px 10px;
    color: white;
}

.hCincoTwo {
    margin: -10px 0px 22px 10px;
    color: white;

}

#main-white {
    position: static;
    color: #fff;
    background-color: #d8d8d840;
    width: 100%;
    margin: 30px auto 0px;
    text-align: center;
}

.main-four {
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
    margin: -10px 0 0 0;
    color: #fff;
    overflow-x: auto;
}

.main-four i {
    font-size: 1.2em;
    color: #555;
}

.main-four h5 {
    margin: 0 auto 20px auto;
}

.main-four-card {
    display: flex;
    justify-content: flex-start;
    flex-direction: row;
}

.main-four-card a {
    border: solid .1px #dddddd54;
    padding: 2px 6px;
    margin: 10px 4px;
    border-radius: 0% 10% 10% 10%;
}

.main-four-card span {
    position: relative;
    top: -6px;
    left: -14px;
}

.main-four-card h4 {
    margin: 0 0 0 15px;
    background: #92929240;
    padding: 0px 10px 0px 10px;
    border-radius: 12% 12% 12% 0%;
}

.main-four-card p {
    margin: 0 0 0 10px;
    font-size: .9em;
}

.body-map {
    width: 375px;
    height: 270px;
    margin: 10px auto 30px auto;
}

.main-five {
    background: black;
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
    margin: -10px 0 0 0;
    color: #fff;
    box-shadow: 0px 10px 10px#bbb;
    overflow-x: auto;
}

.main-five i {
    font-size: 1.2em;
    color: #555;
}

.main-five h5 {
    margin-left: 10px;
}

.main-five-card {
    height: 370px;
    margin: 0 10px;
    border: solid .5px #e23a2890;
    display: flex;
    justify-content: flex-start;
    flex-direction: column;
}

.main-five-card a {
    border: solid .1px #dddddd54;
    margin: 0px 5px 20px 10px;
    width: 500px;
    border-radius: 3% 3% 3% 3%;
}

.main-five-card span {
    position: relative;
    top: -6px;
    left: -14px;
}

.main-five-card h4 {
    margin: 0 5px 0 10px;
}

.main-five-card p {
    margin: 0 0 0 10px;
    font-size: .9em;
}

.mini-profile {
    height: 25px;
    border-radius: 50%;
    margin: 10px 0 0 10px;
    padding: 0 15px 0 0;
}

a.nuxt-link-exact-active {
    background-color: #e23a2890;
    color: #fff;
    border-radius: 0% 10% 10% 10%;
}

.main-l-trat {
    width: 95%;
    text-align: left;
    margin: -10px auto 20px auto;
    display: flex;
    flex-flow: row wrap;
    align-items: flex-start;
    justify-content: center;
    align-self: center;
}

.dot-index {
    cursor: pointer;
    transition: all .3s ease-in;
    background-color: #d8d8d840;
    margin: 10px 16px;
    padding: 10px;
    font-size: 1em;
    text-transform: uppercase;
    font-weight: bold;
    border-radius: 5% 4% 15%;
    border: solid .5px;
}

.dot-index:Hover {
    color: #fff;
    border: solid .5px #e23a28;
}

.dot-index {
    margin: 5px 10px;
    padding: 8px;
    font-size: .6em;
}

.dotHover {
    background-color: #d8d8d840;
    color: #ddd;
    border: solid .5px #e23a28;
}

.dot:hover {
    background-color: #d8d8d840;
}

.dot:active {
    color: dbd1d1;
    background-color: #d8d8d8;
}

.selectTitle {
    text-shadow: -2px 2px 5px #e23a28,
        -2px -2px 5px #e23a28,
        2px 2px 5px #e23a28,
        2px -2px 5px #e23a28;
    color: #fff;
}

.selectTitleHover {
    color: #fff;
    border: solid .5px #e23a28;
    opacity: 1s;
}

.selectTitleHover span {
    font-size: 1.2em;
}

.white {
    color: #ffffff;
    margin: 0;
}

.homeTwo {
    display: flex;
    flex-flow: row wrap;
    align-items: center;
    justify-content: space-evenly;
    align-self: center;
    font-size: .9em;
    width: 95%;
    margin: auto;
    font-weight: bold;
    color: #dbd1d1;
}

.homeTwo div {
    padding-top: 5px;
    padding-left: 10px;
    padding-right: 10px;

}

.homeTwo a {
    font-size: 1em;
    margin: auto;
    font-weight: bold;
    color: #dbd1d1;
}

.homeTwoDot:hover {
    text-shadow: -1px 1px 10px #fff;
    cursor: pointer;
}

.hr {
    width: 95%;
    border: solid .3px #e23a2840;
    margin: 30px auto 0px auto;
}


@media only screen and (max-width: 369px) {}
</style>