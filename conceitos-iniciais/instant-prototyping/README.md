# Instant Prototyping

Para conseguirmos trabalhar com o Vue sem a necessidade de iniciar um projeto a cada exemplo, utilizaremos um recurso do [Vue CLI](https://cli.vuejs.org/) chamado **Instant Prototyping**, que nada mais é do que um componente Vue condensado em um único arquivo e é **servido** para o cliente.

1. Instalação do Vue CLI:
```sh
npm install -g @vue/cli @vue/cli-service-global
# or
yarn global add @vue/cli @vue/cli-service-global
```
2. Criação do arquivo **App.vue**, que vai receber o nosso componente:
```sh
mkdir meu-componente
cd meu-componente
touch App.vue
```
3. Execução do servidor que vai **servir** o nosso componente como uma aplicação.:
```sh
vue serve
```

Para conferir se o nosso instant prototyping está funcionando copie o código do arquivo **App.vue** acima, cole no seu componente, execute o servidor e abra o localhost no navegador.

![Localhost executando na 8080](./assets/localhost.png)

>Originalmente a nossa aplicação estará sendo executada na porta **8080**, caso esta porta esteja ocupada ele executará na **8081**.
