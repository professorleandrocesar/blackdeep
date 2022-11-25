<template>
  <div>
    <div class="nav-bottom">
      <a href="https://deepacupuntura.com">
        <i class="fa-solid fa-globe"></i>
        <h5>SITE</h5>
      </a>
      <a
      href='https://api.whatsapp.com/send?phone=5521971305858%20&text=Ol%C3%A1%20Leandro%20Cesar,%20fiquei%20interessado(a)%20no%20seus%20serviços%20de%20Acupuntura,%20me%20chamo%20'>
      <i class="fa-brands fa-whatsapp"></i>
      <h5>WHATSAPP</h5>
      </a>
      <a href="https://instagram.com/deepacupuntura">
        <i class="fa-brands fa-instagram-square"></i>
        <h5>INSTAGRAM</h5>
      </a>
      <a href="https://goo.gl/maps/4bbTEUKuQDbqotTG9">
        <i class="fa-solid fa-location-dot"></i>
        <h5>LOCALIZAÇÃO</h5>
      </a>
    </div>
  </div>
</template>

<style scoped>
h5 {
  margin: 9px 0 13px 0;
  font-size: .6em;
}

i {
  font-size: 1.1em;
}

/*
  background-color: #6a0707;
  background-color: black;
*/

.nav-bottom {
  position: fixed;
  bottom: .1px;
  width: 100%;
  background-color: black;
  color: #fff;
  display: flex;
  flex-flow: row wrap;
  align-items: center;
  justify-content: space-around;
  align-self: center;
  line-height: 0;
  border-radius: 10% 10% 0% 0%;
  box-shadow: 0px .5px 5px #e23a2890;
}

.nav-bottom div {
  cursor: pointer;
}

.nav-bottom div h5 {
  margin: 0;
  padding: 0;
  font-size: 1em;
}

.nav-bottom a {
  text-decoration: none;
  cursor: pointer;
  display: flex;
  flex-flow: column wrap;
  align-items: center;
  justify-content: center;
  align-self: center;
  color: #ffffff80;
  font-size: .9em;
  margin: 10px 0 0px 0;
}

.nav-bottom a:hover i {
  color: #ffffff;
}

.nav-bottom a.nuxt-link-exact-active {
  color: #fff;
}
</style>