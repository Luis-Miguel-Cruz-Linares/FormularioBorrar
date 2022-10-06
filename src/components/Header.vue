<template>
    <div class="container mt-3">
        <div class="row">
          <div class="col-12 col-md-3">
            <h1>Formularios</h1>
          </div>

          <div class="row">
          <div class="col-12 col-md-3">
            <img :src="url" :alt="alt" width="100">
          </div>
          </div>
          
        </div>
      </div>
    <hr/>
</template>

<script>
    export default {
      data: () => ({
      url: "https://cdn.svgporn.com/logos/vue.svg",
      alt: "Vue.js", 
      nombre:"",
      edad:0,
      correo: "",
    }),
    
    };
    
  </script>