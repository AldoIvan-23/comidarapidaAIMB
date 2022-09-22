<template>
  <header>
    <div class="card p-2 bg-transparent border-0 justify-content-center row">
      <h1 class="title-card">EL SABOR MEXICANO!</h1>
      <center><h3>Aldo Ivan Martinez Balderas | 4°B</h3></center>
    </div>
  </header>
  <main>

      <div class="card p-3 bg-transparent">
        <h1 class="card-title">¡Haz tu pedido ahora!</h1>
      </div>

      <div class="contenedor">
      <card url="https://kfc.com.mx/Content/OnlineOrderingImages/Menu/Items/lg2x/hamburguesa-big-krunch.jpg?v=0.2" 
      nombre ="Hamburguesa Big Krunch"
      detalles="Tu ingrediente favorito en una masa fresca y hecha a mano"
      Ingredientes="Pollo"
      precio="220.00"
      >
      </card>
  
      <card url="https://kfc.com.mx/Content/OnlineOrderingImages/Menu/Items/lg2x/papas-familiares.jpg?v=0.2" 
      nombre ="Papas francesas"
      detalles="Ricas papas naturales corte frances "
      Ingredientes="papas naturales y frescas"
      precio="210.00"
      >
      </card>
  
      <card url="https://kfc.com.mx/Content/OnlineOrderingImages/Menu/Items/lg2x/KidsBucket-KeTira-Footy.jpg?v=0.2" 
      nombre ="Paquete niños"
      detalles="Consiente a los niños de la casa con este combo"
      Ingredientes="papas, pollo, jugo en caja."
      precio="330.00"
      >
      </card>
  
      <card url="https://kfc.com.mx/Content/OnlineOrderingImages/Menu/Items/lg2x/chickn-share-mixto.jpg?v=0.2" 
      nombre ="Chicken's share"
      detalles="Todo perfectamente horneado para un sabor irresistible…"
      Ingredientes="Jalapeño, queso mozzarella,provolone,queso cheddar, pollo y cebolla"
      precio="212.20"
      >
      </card>
  
  
      <card url="https://kfc.com.mx/Content/OnlineOrderingImages/Menu/Items/lg2x/refresco-2-l.jpg?v=0.2" 
      nombre ="Bebidas"
      detalles="Refresque su dia y su comida con nuestra variedad de bebidas."
      Ingredientes=""
      precio="18.00"
      >
    </card>

      <card url="https://assets.dominos.com.mx/dev/webOptimized/especialidad/TEXAS/TEXAS.png" 
      nombre ="CHICKEN HAWAIANA"
      detalles="La pizza más tropical que tenemos. Pollo, tocino, piña, salsa mango habanero."
      Ingredientes="Pollo, Tocino, Piña y Salsa de Mango Habanero"
      precio="111.00"
      >
      </card>
    </div>
  </main>
<!-- Footer -->
<footer class="page-footer font-small pt-5">

  <div class="text-center text-md-left">
    <div class="row">
      <div class="col-md-6 mt-md-0 mt-3">
        <a href="https://www.dominos.com.mx/tiendas">Nuestras sucursales</a><br>
        <a href="https://www.dominos.com.mx/facturacion">Facturación Electrónica</a><br>
        <a href="https://www.dominos.com.mx/terminos-y-condiciones">Términos y condiciones</a><br>

      </div>


  
      <div class="col-md-6 mb-md-0 mb-3">

    
        <a href="https://www.dominos.com.mx/politicas-de-privacidad">Aviso de privacidad</a><br>
        <a href="http://responsabilidad.dominos.com.mx/viviendoenequilibrio/alime">Viviendo en Equilibrio</a><br>
        <a href="https://www.dominos.com.mx/quienes-somos">¿Quienes somos?</a><br>
        
      </div>


    </div>


  </div>
  <div class="footer-copyright text-center py-4">© 2022 Copyright:
    <a href="/"> Comida Rapida</a>
  </div>

</footer>

</template>
<script>
  import Card from "./components/Card.vue"
  
  export default{
    components:{
      Card
    },
  };
</script>
<style scoped>
  *{
    margin: 0;
  }
  a{
    text-decoration: none;
  }
header{
  background-image: url(https://eldiariony.com/wp-content/uploads/sites/2/2021/11/Comida-ra%CC%81pida-y-diabetes.jpg?quality=60&strip=all&w=1200);
  height: 60vh;
  background-repeat: no-repeat;
  background-size:cover;
}
header h1 {
  color: green;
  font-size: 50px;
  font-weight: 800;
  font-family: 'Oswald', sans-serif;
  margin-top: 150px;
  text-align: center;
  backdrop-filter: blur(2px);
}
@font-face {
  font-family: 'Oswald', sans-serif;
  src: url('https://fonts.googleapis.com/css2?family=Oswald:wght@600&display=swap');
}
.btn{
  color:white;
  border:solid red .1rem;
  width: 150px;
  backdrop-filter: blur(5px);
  font-weight: 600;
}
.contenedor{
  width: 90%;
}
@media screen and (max-width: 380px){
    header h1{
      font-size: 30px;
      margin-top: 50px;
    }
    .btn{
      width:100px;
      font-weight: 300;
    }
  }
  footer{
    height: 30vh;
  }
  footer a{
    color: blue;
  }
</style>