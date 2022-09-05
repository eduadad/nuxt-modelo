<template> 
  <div>
<h1 class="title">
  Lista de Produtos
</h1>

<div class="columns">
  <div class="column is-3">
    First column
  </div>
  <div class="column is-9">


    
    <div class="columns">
      <div class="column">
                <article class="notification is-primary">
<b-image class="image"  :src="require('@/assets/arma3.png')"></b-image>          
          <p class="title">AK47</p>
          <p class="subtitle">R$1500,00</p>
          <router-link :to="{ path: '/produto-show' }">Saber mais</router-link>
        </article>
      </div>
      <div class="column">
        <article class="notification is-info">
          <b-image class="image"  :src="require('@/assets/arma4.jpg')"></b-image> 
          <p class="title">Pistola</p>
          <p class="subtitle">R$800,00</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div>
      <div class="column">
        <article class="notification is-warning">
          <b-image class="image"  :src="require('@/assets/arma6.png')"></b-image
          <p class="title">Revolver</p>
          <p class="subtitle">R$1000,00</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div>
    </div>

 <div class="columns">
      <div class="column">
                <article class="notification is-primary">
<b-image class="image"  :src="require('@/assets/arcoeflecha.jpg')"></b-image>          
          <p class="title">Arco e Flecha</p>
          <p class="subtitle">R$1000,00</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div>
      <div class="column">
        <article class="notification is-info">
          <b-image class="image"  :src="require('@/assets/espada.jpg')"></b-image> 
          <p class="title">Espada viking</p>
          <p class="subtitle">R$1000,00</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div>
      <div class="column">
        <article class="notification is-warning">
          <b-image class="image"  :src="require('@/assets/machado.jpg')"></b-image
          <p class="title">Machado viking</p>
          <p class="subtitle">R$1000,00</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div>
    </div>

     <div class="columns">
      <div class="column">
                <article class="notification is-primary">
<b-image class="image"  :src="require('@/assets/karambit.jpg')"></b-image>          
          <p class="title">Karambit</p>
          <p class="subtitle">R$1000,00</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div>
      <div class="column">
        <article class="notification is-info">
          <b-image class="image"  :src="require('@/assets/machete.jpg')"></b-image> 
          <p class="title">Machete</p>
          <p class="subtitle">R$600,00</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div>
      <div class="column">
        <article class="notification is-warning">
          <b-image class="image"  :src="require('@/assets/download.jpg')"></b-image
          <p class="title">Faca borboleta </p>
          <p class="subtitle">R$500,00</p>
          <router-link :to="{ path: '/imagens' }">Exemplo de link</router-link>
        </article>
      </div>
    </div>

    
  </div>
</div>

    
  </div>
</template>