<template>
  <div>
    <the-header title="RememberMe"></the-header>
    <stored-resources :resources="storedResources"> </stored-resources>
  </div>
</template>

<script>
  import StoredResources from './Components/learning-resources/StoredResources.vue';
  import TheHeader from './Components/layouts/TheHeader.vue';

  export default {
    components: {
        StoredResources,
        TheHeader
    },
    data(){
      return {
        storedResources: [
          {
            id: 'official-guide',
            title: 'Offical Guide',
            description: 'The official Vue JS Documentation',
            link: 'https://vuejs.org'
          },
          {
            id: 'google',
            title: 'Google',
            description: 'Google',
            link: 'www.google.com'
          }
        ]
      };
    }
  }
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

  * {
    box-sizing: border-box;
  }

  html {
    font-family: 'Roboto', sans-serif;
  }

  body {
    margin: 0;
  }
</style>