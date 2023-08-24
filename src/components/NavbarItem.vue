<template>
  <div id="nav">
    <router-link id="logo-url" to="/">
      <img id="logo" src="@/assets/m 1.png" :alt="alt">
    </router-link>

       <router-link class="bot1" to="/">Fazer Pedido</router-link>
      

    <router-link class="bo2" to="/pedidos">Pedidos</router-link>
    
   
  </div>




</template>
  
<script script>

</script>
  
<style scoped>
#nav {
  background: linear-gradient(183deg, rgba(155, 155, 155, 0.54) 0%, rgba(217, 217, 217, 0.00) 100%);
  padding: 15px 50px;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  width: 1905px;
  height: 100px;
  flex-shrink: 0;
}

#nav #logo-url {
  margin: auto;
  margin-left: 0;
}

#logo {
  width: 70px;
  height: 70px;
}

router-link{

  text-decoration: none;
  transition: .5s;
  width: 221px;
height: 71px;
flex-shrink: 0;
color: #FFF;
font-family: Inter;
font-size: 32px;
font-style: normal;
font-weight: 400;
line-height: normal;


}

router-link:hover {
  color: #FFF;
}


</style>
