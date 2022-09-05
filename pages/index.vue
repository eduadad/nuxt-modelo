<template>
  <section class="section">
<b-carousel>
      <b-carousel-item>
        <b-image class="image" :src="require('@/assets/paisagem2.webp')"></b-image>
      </b-carousel-item>
      <b-carousel-item>
        <b-image class="image" src="https://picsum.photos/id/432/1230/300"></b-image>
      </b-carousel-item>      
      <b-carousel-item>
        <b-image class="image" src="https://picsum.photos/id/433/1230/300"></b-image>
      </b-carousel-item>            
    </b-carousel>

    <div class="columns mt-5">
      <div class="column is-4">
        <article class="notification is-primary">
<b-image class="image"  :src="require('@/assets/arma3.png')"></b-image>          
          <p class="title">AK47</p>
          <p class="subtitle">R$1500,00</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div>
      <div class="column is-4">
        <article class="notification is-info">
          <b-image class="image"  :src="require('@/assets/arma4.jpg')"></b-image> 
          <p class="title">Pistola</p>
          <p class="subtitle">R$800,00</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div>  
            <div class="column is-4">
        <article class="notification is-warning">
          <b-image class="image"  :src="require('@/assets/arma6.png')"></b-image
          <p class="title">Revolver</p>
          <p class="subtitle">R$1000,00</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div> 
            
    </div>


    



  </section>
</template>

