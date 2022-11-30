<template>
  <div>
    
    <div class='profile'>
      <img src='/img/MyLogoBold.svg' alt=''>

      <div>
        <h1>Deep Acupuntura</h1>
        <h4>| Clinica de Medicina Chinesa | </h4>
      </div>
      
    </div>
    
    <div class='main-one'>
    <div>
      <h2>Black Descontos</h2>
      <h3>Descontos sobre desconto<br>jamais visto!</h3>
    </div>
  </div>
  <div class='main-tree'>
    <div>
    
      </div>
      <div class='homeTwo'>
        <div class='homeTwoDot'>
          <a >Acupuntura Sistêmica</a>
        </div>
        <div class='homeTwoDot'>
          <a >Craniopuntura</a>
        </div>
        <div class='homeTwoDot'>
          <a >Auriculoterapia</a>
        </div>
        <div class='homeTwoDot'>
          <a >Ventosaterapia</a>
        </div>
        <div class='homeTwoDot'>
          <a >Gua Sha</a>
        </div>
        <div class='homeTwoDot'>
          <a >Fórmulas Magistrias Chinesas</a>
        </div>

        <!--
              // <div @click='acupuntura()' class='homeTwoDot' :class='{ selectTitle: aplicarAcu }'>Acupuntura Sistêmica</div>
              // <div @click='craniopuntura()' class='homeTwoDot' :class='{ selectTitle: aplicarCran }'>Craniopuntura</div>
              // <div @click='auriculo()' class='homeTwoDot' :class='{ selectTitle: aplicarAur }'>Auriculoterapia</div>
              // <div @click='ventosa()' class='homeTwoDot' :class='{ selectTitle: aplicarVen }'>Ventosaterapia</div>
              -->
      </div>
      <br>
    <div class='main-two'>
    <div>
      <table>
        <thead>
          <th>
            50%
          </th>
          <th>
            40%
          </th>
          <th>
            30%
          </th>
          <th>
            20%
          </th>
        </thead>
        <tfoot>
          <tr>
            <td colspan="4">*Valores referente à pacote com 4 sessões/mês no plano recorrente;</td>
          </tr>
        </tfoot>
        <tbody>
          <tr>

            <td><s>R$ 200,00</s><br>R$ 100,00 </td>
            <td><s>R$ 200,00</s><br>R$ 120,00</td>
            <!--
            <td><s>R$ 200,00</s><br>R$ 140,00</td>
            <td><s>R$ 200,00</s><br>R$ 160,00</td>
            -->
          </tr>
          <tr>
            <td><s>5 vagas</s></td>
            <td>7 vagas</td>
            <td>15 vagas</td>
            <td>20 vagas</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
  <div>
    <br>
    <h5 class='hCincoTwo' style='margin-right: 10px;'><i class="fa-solid fa-angle-right"></i> Regulamento Básico</h5>
    <ul style='margin-right: 10px;'>
      <li>Modalidade: Plano Recorrente Mensal (PRM);</li>
      <li>Primeiro pagamento deve ser feito até o dia 05 de dezembro/22</li>
      <li>Após, Pagamento deve ser feito até o dia 10 de cada mês;</li>
      <li>Desconto é referente ao pacote de 4 sessões por mẽs, sendo 1 sessão por semana;</li>
      <li>Sem reposição, se faltar uma semana, perde aquela sessão;</li>
      <li>Escolha o dia e horário da semana, para fazer de forma contínua;</li>
      <li>Em caso de falta, tentar marcar na mesma semana, em outro dia e horário;</li>
      <li>Se não cumprir tais regras, serás 'retirado' da promoção, podendo ser dado a outra pessoa;</li>
      <li>Saindo do plano, pode-se indicar alguém para ficar no seu lugar (mesmo dia/horário);</li>
    </ul>
  </div>
  <br>
  <h5 class='hCincoTwo' style='margin-right: 10px;'><i class="fa-solid fa-angle-right"></i> Regras básicas de acordo? Se sim, então...</h5>
      <br>
      <div>
        <h5 class='hCincoTwo' style='margin-right: 10px;'><i class="fa-solid fa-angle-right"></i> Escolha o desconto:</h5>
        
      </div>
      <div class='main-l-trat'>
        <a class='dot-indexOk'>50%</a>
        <nuxt-link to="/40" class='dot-index'>40%</nuxt-link>
        <nuxt-link to="/30" class='dot-index'>30%</nuxt-link>
        <nuxt-link to="/20" class='dot-index'>20%</nuxt-link>
      </div>
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
  },
  data() {
      return {
          aplicar : '',
          output: '',
          aplicarAcu: '',
          aplicarAur: '',
          aplicarVen: '',
          aplicarCran: '',
          aplicarAcu: '',
          aplicarAur: '',
          aplicarVen: '',
          aplicar: '',
          aplicarTwo: '',
          aplicarTree: '',
          aplicarFour: '',
          aplicarFive: '',
          aplicarSix: '',
          aplicarSeven: '',
          aplicarEight: '',
          aplicarNine: '',
          aplicarTen: '',
          aplicarEleven: '',
          aplicarTwelve: '',
          aplicarThirteen:'' ,
          aplicarFourteen: '',
          rAnsiedade:'50%',
          rDepressao:'40%',
          rEstresse:'30%',
          rCervicalgia:'20%',
          rLombalgia: 'Lombalgia',
          rEnxaqueca: 'Enxaqueca',
          rCefaleia:'Cefaleia',
          rBaixaImunidade:'Baixa Imunidade',
          rBurnout:'Burnout',
          rLaringite:'Laringite',
          rInsonia:'Insônia',
          rZumbido:'Zumbido',
          rLabirintite:'Labirintite',
          rSinusite:'Sinusite',
      }
  },
  methods: {
    acupuntura() {
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = false,
          this.aplicar = true,
          this.aplicarTwo = true,
          this.aplicarTree = true,
          this.aplicarFour = true,
          this.aplicarFive = true,
          this.aplicarSix = true,
          this.aplicarSeven = true,
          this.aplicarEight = true,
          this.aplicarNine = true,
          this.aplicarTen = true,
          this.aplicarEleven = true,
          this.aplicarTwelve = true,
          this.aplicarThirteen = true,
          this.aplicarFourteen = true,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
    },
    craniopuntura() {
          this.aplicarAcu = false,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = true,
          this.aplicar = true,
          this.aplicarTwo = true,
          this.aplicarTree = true,
          this.aplicarFour = true,
          this.aplicarFive = true,
          this.aplicarSix = true,
          this.aplicarSeven = true,
          this.aplicarCran = true,
          this.aplicarEight = true,
          this.aplicarNine = true,
          this.aplicarTen = true,
          this.aplicarEleven = true,
          this.aplicarCran = true,
          this.aplicarTwelve = true,
          this.aplicarThirteen = true,
          this.aplicarFourteen = true,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
    },
    auriculo() {
          this.aplicarAur = true,
          this.aplicarAcu = false,
          this.aplicarVen = false,
          this.aplicar = true,
          this.aplicarCran = false,
          this.aplicarTwo = true,
          this.aplicarTree = true,
          this.aplicarFour = true,
          this.aplicarFive = true,
          this.aplicarSix = true,
          this.aplicarSeven = true,
          this.aplicarEight = true,
          this.aplicarNine = true,
          this.aplicarTen = true,
          this.aplicarEleven = true,
          this.aplicarTwelve = true,
          this.aplicarThirteen = true,
          this.aplicarFourteen = true,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
    },
    ventosa() {
          this.aplicarVen = true,
          this.aplicarCran = true,
          this.aplicarAcu = false,
          this.aplicarAur = false,
          this.aplicar = false,
          this.aplicarCran = false,
          this.aplicarTwo = false,
          this.aplicarTree = true,
          this.aplicarFour = true,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
    },
      ansiedade() {
          this.aplicarAcu = true,
          this.aplicarAur = true,
          this.aplicarCran = false,
          this.aplicarVen = false,
          this.aplicar = true,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rDepressao = 'depressão',
          this.rAnsiedade = `<span><h4>Ansiedade</h4></span>
           <h4 @click='ansiedade()' class='dot-index' :class='{ selectTitleHover: aplicar }' v-html='rAnsiedade'></h4>
        <h4 @click='depressao()' class='dot-index' :class='{ selectTitleHover: aplicarTwo }' v-html='rDepressao'></h4>
        <h4 @click='estresse()' class='dot-index' :class='{ selectTitleHover: aplicarFive }' v-html='rEstresse'></h4>
        <h4 @click='cervicalgia()' class='dot-index' :class='{ selectTitleHover: aplicarTree }' v-html='rCervicalgia'>`,
          this.rEstresse='',
          this.rCervicalgia='',
          this.rLombalgia= '',
          this.rEnxaqueca= '',
          this.rCefaleia='',
          this.rBaixaImunidade=' ',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      depressao(){
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = true,
          this.aplicar = false,
          this.aplicarTwo = true,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = `<span><h4>Depressão</h4></span>
          <br>
          <span class='white'>é um transtorno mental caracterizado por tristeza profunda persistente 
          e aversão a atividades. Pode afetar os pensamentos, comportamentos, sentimentos e o bem-estar de uma pessoa.</span>`,
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      estresse() {
          this.aplicarAcu = true,
          this.aplicarAur = true,
          this.aplicarVen = false,
          this.aplicarTwo = false,
          this.aplicarCran = false,
          this.aplicar = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = true,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse=`<span><h4>Estresse</h4></span>
          <br>
          <span class='white'>É causado pela ansiedade e pela depressão devido à mudança brusca no 
          estilo de vida e a exposição a um determinado ambiente, que leva a pessoa a sentir um determinado tipo de angústia. </span>`,
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      cervicalgia(){
          this.aplicarAcu = true,
          this.aplicarAur = true,
          this.aplicarVen = true,
          this.aplicar = false,
          this.aplicarCran = false,
          this.aplicarTwo = false,
          this.aplicarTree = true,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia=`<span><h4>Cervicalgia</h4></span>
          <br>
          <span class='white'>Dor no pescoço e ombro que varia em intensidade, podendo ser incômoda ou 
          como um choque elétrico desde o pescoço até o braço.</span>`,
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      lombalgia(){
          this.aplicarAcu = true,
          this.aplicarAur = true,
          this.aplicarVen = true,
          this.aplicarCran = true,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = true,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= `<span><h4>Lombalgia</h4></span>
          <br>
          <span class='white'>Uma condição dolorosa comum que afeta a parte inferior da coluna.
A dor lombar é causada por uma lesão em um músculo (tensão) ou ligamento (entorse). As causas comuns incluem 
levantamento impróprio, má postura, falta de exercícios físicos regulares, fratura, disco rompido ou artrite.</span>`,
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      enxaqueca() {
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = true,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = true,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= `<span><h4>Enxaqueca</h4></span>
          <br>
          <span class='white'>Dor de cabeça de intensidade variável, muitas vezes acompanhada de náuseas e sensibilidade à luz e ao som.
Às vezes, as enxaquecas são precedidas por sintomas de alerta. Os gatilhos incluem alterações hormonais, certos alimentos e bebidas, estresse 
e exercícios físicos.</span>`,
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      cefaleia () {
          this.aplicarAcu = true,
          this.aplicarAur = true,
          this.aplicarVen = false,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = true,
          this.aplicarCran = true,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia=`<span><h4>Cefaléia</h4></span>
          <br>
          <span class='white'>Uma sensação dolorosa em qualquer parte da cabeça, 
          desde aguda até incômoda, podendo ocorrer junto com outros sintomas.</span>`,
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      baixaImunidade () {
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = false,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = true,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade=`<span><h4>Baixa Imunidade</h4></span>
          <br>
          <span class='white'>pode ser percebida quando o organismo dá alguns sinais, indicando que as defesas do organismo estão baixas e que o sistema imunológico não está sendo capaz de combater 
          os agentes infecciosos, como vírus e bactérias, o que pode fazer com que a pessoa fique doente com mais frequência.</span>`,
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      burnOut() {
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = true,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = true,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout=`<span><h4>Burnout</h4></span>
          <br>
          <span class='white'>A síndrome de burnout é um distúrbio psíquico causado pela exaustão extrema, sempre relacionada ao trabalho de um indivíduo. Essa condição 
          também é chamada de “síndrome do esgotamento profissional” e afeta quase todas as facetas da vida de um indivíduo.</span>`,
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      laringite() {
          this.aplicarAcu = true,
          this.aplicarAur = true,
          this.aplicarVen = false,
          this.aplicarCran = true,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = true,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite=`<span><h4>Laringite</h4></span>
          <br>
          <span class='white'>é a inflamação da laringe (região das vias aéreas onde ficam localizadas as cordas vocais), que conecta a faringe à traqueia e faz parte do sistema respiratório. A inflamação 
          dessa região pode ser causada por vírus (mais prevalente), bactérias, inalação de agentes alérgicos ou esforço excessivo da voz.</span>`,
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      insonia() {
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = true,
          this.aplicarCran = true,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia=`<span><h4>Insônia</h4></span>
          <br>
          <span class='white'>é caracterizada pela dificuldade de dormir ou conseguir manter um sono contínuo sem ser interrompido durante a noite. Cerca de 30% a 50% dos brasileiros sofrem com a insônia, 
          que pode se manifestar por diversas razões, como estresse, ansiedade, depressão, dor crônica e uso de certos medicamentos.</span>`,
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      zumbido() {
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = true,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = true,
          this.aplicarThirteen = false,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido=`<span><h4>Zumbido</h4></span>
          <br>
          <span class='white'>Também chamado de Sibilo ou Tinido, pode ser definido como uma ilusão auditiva, ou seja, uma sensação sonora não relacionada com uma fonte externa de estimulação.</span>`,
          this.rLabirintite='Labirintite',
          this.rSinusite='Sinusite'
      },
      labirintite() {
          this.aplicarAcu = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicarCran = true,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = true,
          this.aplicarFourteen = false,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite=`<span><h4>Labirintite</h4></span>
          <br>
          <span class='white'>Labirintite é o nome popular que se dá a todos os transtornos do labirinto, uma estrutura interna do ouvido composta pela cóclea (imprescindível para a 
          nossa audição), pelo vestíbulo e pelos canais semicirculares (que têm papel na manutenção do nosso equilíbrio).</span>`,
          this.rSinusite='Sinusite'
      },
      sinusite() {
          this.aplicarAcu = true,
          this.aplicarCran = true,
          this.aplicarAur = false,
          this.aplicarVen = false,
          this.aplicar = false,
          this.aplicarTwo = false,
          this.aplicarTree = false,
          this.aplicarFour = false,
          this.aplicarFive = false,
          this.aplicarSix = false,
          this.aplicarSeven = false,
          this.aplicarEight = false,
          this.aplicarNine = false,
          this.aplicarTen = false,
          this.aplicarEleven = false,
          this.aplicarTwelve = false,
          this.aplicarThirteen = false,
          this.aplicarFourteen = true,
          this.rAnsiedade = 'ansiedade',
          this.rDepressao = 'Depressão',
          this.rEstresse='Estresse',
          this.rCervicalgia='Cervicalgia',
          this.rLombalgia= 'Lombalgia',
          this.rEnxaqueca= 'Enxaqueca',
          this.rCefaleia='Cefaleia',
          this.rBaixaImunidade='Baixa Imunidade',
          this.rBurnout='Burnout',
          this.rLaringite='Laringite',
          this.rInsonia='Insônia',
          this.rZumbido='Zumbido',
          this.rLabirintite='Labirintite',
          this.rSinusite=`<span><h4>Sinusite</h4></span>
          <br>
          <span class='white'>é a inflamação das mucosas dos seios da face, região do crânio formada por cavidades ósseas ao redor do nariz, maçãs do rosto e olhos. Os 
          seios da face dão ressonância à voz, aquecem o ar inspirado e diminuem o peso do crânio, o que facilita sua sustentação.</span>`
      }
  } 
}
</script>

<style scoped>
s {
  color: red
}
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
  cursor:pointer;
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

.main-one {
  display: flex;
  justify-content: center;
  flex-direction: row;
  padding: 10px 0 15px 0;
  background: black;
}

.main-one h2 {
  text-align: center;
  margin: 13px auto -20px 0px;
    font-size: 1.5em;
    color: black;
    text-shadow: -2px 2px 5px #e23a28,
      -2px -2px 5px #e23a28,
      2px 2px 5px #e23a28,
      2px -2px 5px #e23a28;
}
.main-one h3 {
  text-align: center;
    font-size: 1.3em;
    color: #00ff00;
    text-shadow: -2px 2px 5px #498f49,
      -2px -2px 5px #498f49,
      2px 2px 5px #498f49,
      2px -2px 5px #498f49;
      line-height: 1;
}

.main-one div {
  margin: 0 0 0 15px;
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
  justify-content: center;
  flex-direction: row;
  background: black;
}

.main-two h2 {
  text-align: center;
  margin: 13px auto -20px 0px;
    font-size: 1.5em;
    color: #fff;
}
.main-two h3 {
  text-align: center;
    font-size: 1.3em;
    color: black;
    text-shadow: -2px 2px 5px #ffffff50,
      -2px -2px 5px #ffffff50,
      2px 2px 5px #ffffff50,
      2px -2px 5px #ffffff50;
}

table {
  color: #fff;
  border-collapse: collapse;
  margin: 0;
}

table th{
  color: #00ff00;
  border: 3px solid #860d0d; 
  font-weight: bold;
  color: #00ff00;
    text-shadow: -2px 2px 5px #498f49,
      -2px -2px 5px #00ff00,
      2px 2px 5px #00ff00,
      2px -2px 5px #00ff00;
}

table td{
  border: 3px solid #860d0d; 
  color: #fff;
  text-align: center;
  font-weight: bold;
}

table tfoot tr td{
  border: transparent; 
  color: #fff;
  font-size:.8em;
  font-weight: bold;
}

.main-two div {
  margin: 0 0 0 15px;
}

.main-two a i {
  font-size: 1.2em;
}

.main-two a:nth-child(1) i,
.main-two a:nth-child(2) i {
  padding-right: 3px;
  margin: 0 0 0 3px;
}

.main-two a:nth-child(2) i {
  padding-right: 4px;
  margin: 0 0 0 4px;
}

.main-two a:nth-child(3) i {
  margin: 0 0 0 3px;
  padding-right: 2px;
}

.main-two a:nth-child(4) i {
  margin: 0 0 0 5px;
  padding-right: 2px;
}

.main-two a {
  margin: 0 0 0 10px;
  color: #ddd;
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
}

.hCincoTwo {
  margin: -10px 0px 22px 10px;

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
  padding: 20px;
  font-size: 1em;
  text-transform: uppercase;
  font-weight: bold;
  border-radius: 5% 4% 15%;
  border: solid .5px;
}

.dot-index:Hover {
  color: #fff;
  border: solid .5px #00ff00;
}

.dot-index {
  margin: 5px 10px;
  padding: 8px;
  font-size: .8em;
}


.dot-index {
  margin: 5px 10px;
  padding: 8px;
  font-size: 1em;
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
  justify-content:space-evenly;
  align-self:center;
  font-size: .9em;
  width: 95%;
  margin:auto;
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