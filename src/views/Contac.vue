<template>
  <div class="container">
    <div class="has-text-contered">
      <h1>Contac Us</h1>
      <img  alt="Vue logo" src="../assets/logo.png" >
      <div class="columns">
        <div class="column">
          <div class="">
              <ContacUsform />
        </div>
      </div>
      
      <div class="column">
        <div class="">
        </div>
      </div>  
    </div>
  </div>
</div>

</template>


<script>
import '../css/bootstrap.min.css'
import '../css/bootstrap-reboot.min.css'
import '../css/style.css'
import '../css/animate.css'
import ContacUsform from '@/components/ContacUsform.vue'
export default {
  components: {
    ContacUsform
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h3 {
      margin: 40px 0 0;
    }
    ul {
      list-style-type: none;
      padding: 0;
    }
    li {
      display: inline-block;
      margin: 0 10px;
    }
    a {
      color: #42b983;
    }
</style>