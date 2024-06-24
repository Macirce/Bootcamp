
<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    Siemano
    <br/>
    <button @click="podbij">kliknij, aby zwiększyć liczbę</button> 
    {{ licznik }}
  </main>
</template>

<script>
export  default {
  data() {
    return{
      licznik:0
    }
  },
  methods: {
    podbij(){
      this.licznik++
    }
  }
}
</script>
