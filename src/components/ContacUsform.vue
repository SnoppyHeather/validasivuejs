<template>
  <div class="contacus">
    <div class="field">
  <label class="label">Name</label>
    <div class="control">
      <input class="input" type="text" placeholder="Enter Your Name">
    </div>
</div>

<div class="field">
  <label class="label">Email</label>
    <div class="control has-icons-left has-icons-right">
      <input class="input" type="email" placeholder="Enter Your Email">
        <span class="icon is-small is-left">
          <i class="fas fa-envelope"></i>
        </span>
    </div>
</div>


<div class="field">
  <label class="label">Message</label>
  <div class="control">
    <textarea class="textarea" placeholder="Enter Your Message"></textarea>
  </div>
</div>

<div class="field">
  <div class="control">
    <label class="checkbox">
      <input type="checkbox">
      I agree to the <a href="#">terms and conditions</a>
    </label>
  </div>
</div>


<div class="field is-grouped">
  <div class="control">
    <button class="button is-link">Submit</button>
  </div>
</div>


  </div>
</template>

<script>
export default {
 
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
</style>
