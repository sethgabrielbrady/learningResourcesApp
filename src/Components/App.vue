<template>
    <ul>
    </ul>
</template>

<script>
    export default {
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
                    id: 'googlr',
                    title: 'Googlr',
                    description: 'Google',
                    link: 'www.google.com'
                }
              ]
          };
      }
    }
</script>