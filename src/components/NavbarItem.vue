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
  background-color: #222;
  border-bottom: 4px solid #111;
  padding: 15px 50px;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}

#nav #logo-url {
  margin: auto;
  margin-left: 0;
}

#logo {
  width: 40px;
  height: 40px;
 
}

router-link {
  color: #fcba03;
  text-decoration: none;
  margin: 12px;
  transition: .5s;
  
}

router-link:hover {
  color: #FFF;
}

</style>
