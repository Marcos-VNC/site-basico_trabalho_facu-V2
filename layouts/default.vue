<template>
  <div>
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>
  
  <script>
export default {
  data() {
    return {
      auth: false,
      user: '',
    }
  },
}
</script>
  
<style>
::-webkit-scrollbar {
  display: none;
}
html {
  width: 100%;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>