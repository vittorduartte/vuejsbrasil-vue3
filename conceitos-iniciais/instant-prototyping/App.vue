<template>
  <div>
    <h1>Instant Prototyping</h1>
    <p>
      Para conseguirmos trabalhar com o Vue sem a necessidade de iniciar um
      projeto a cada exemplo, utilizaremos um recurso do
      <a href="https://cli.vuejs.org/">Vue CLI</a> chamado <strong>Instant Prototyping</strong>, que nada mais é do que
      um componente Vue condensado em um único arquivo e é
      <strong>servido</strong> para o cliente.
    </p>
    <br />
    <ul class="learning-list">
      <li class="learning-list__item">Instalação do Vue CLI:</li>
      <div class="code-block">
        <p>npm install -g @vue/cli @vue/cli-service-global</p>
        <p># or</p>
        <p>yarn global add @vue/cli @vue/cli-service-global</p>
      </div>
      <li class="learning-list__item">
        Criação do arquivo <strong>App.vue</strong>, que vai receber o nosso
        componente:
      </li>
      <div class="code-block">
        <p>$ touch App.vue</p>
      </div>
      <li class="learning-list__item">
        Execução do servidor que vai <strong>"servir"</strong> o nosso componente como uma aplicação.
      </li>
      <div class="code-block">
        <p>$ vue serve</p>
      </div>
    </ul>
    <br />
  </div>
</template>

<script>
export default {
  data() {
    return {
      
    }
  },
};
</script>

<style scoped>
* {
  font-family: "Courier New", Courier, monospace;
}
.code-block {
  width: 90%;
  margin: 5px auto;
  padding: 15px;
  border-radius: 5px;
  background: #efefef;
}

.learning-list {
  list-style-type: decimal;
}
</style>