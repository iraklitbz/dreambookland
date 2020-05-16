<template>
    <div class="body-content password-reset-page container max-width-adaptive-xs">



<form class="password-reset-form">
  <div class="text-component text-center margin-bottom-md">
    <h1>Forgot your password?</h1>
    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
  </div>

  <div class="margin-bottom-sm">
    <label class="form-label margin-bottom-xxxs" for="inputEmail1">Email</label>
    <input class="form-control width-100%" type="email" name="inputEmail1" id="inputEmail1" placeholder="email@myemail.com">
  </div>

  <div class="margin-bottom-sm">
    <button class="btn btn--primary btn--md width-100%">Request reset link</button>
  </div>

  <div class="text-center">
    <p class="text-sm"><a href="/login">&larr; Back to login</a></p>
  </div>
</form>

    </div>

</template>

<script>


export default {

  mounted(){
 
  },
  destroyed() { // remove the JS code once the component has been destroyed
   
    }
}
</script>

<style lang="scss">




</style>



