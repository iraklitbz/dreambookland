<template>
  <div class="body-content contact-page">

<section class="contact-v3 margin-top-lg">
  <div class="container max-width-xs margin-bottom-lg">
    <div class="text-component text-center">
      <h1>Contact Us</h1>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ducimus eos impedit nesciunt voluptates magni vero itaque.</p>
    </div>
  </div>

  <div class="container max-width-adaptive-md">
    <div class="grid gap-lg">
      <div class="col-6@md">
        <dl class="details-list-v2 ">
          <div class="details-list-v2__item">
            <dt class="details-list-v2__dt">Address</dt>
            <dd class="details-list-v2__dd">
              86  Whitby Road <br>IP20 6JA <br>London, UK
            </dd>
          </div>

          <div class="details-list-v2__item">
            <dt class="details-list-v2__dt">Email</dt>
            <dd class="details-list-v2__dd">
              <a href='mailto:webmaster@example.com'>hello@myemail.com</a>
            </dd>
          </div>

          <div class="details-list-v2__item">
            <dt class="details-list-v2__dt">Phone</dt>
            <dd class="details-list-v2__dd">
              <a href='tel:+44 7656 6455'>+44 7656 6455</a> <br><small class='color-contrast-medium'>Mon - Fri, 9AM - 5PM</small>
            </dd>
          </div>
        </dl>
      </div>

      <div class="col-6@md">
        <form>
          <div class="margin-bottom-sm">
            <label class="form-label margin-bottom-xxs" for="contactName">Name</label>
            <input class="form-control width-100%" type="text" name="contactName" id="contactName" required>
          </div>
      
          <div class="margin-bottom-sm">
            <label class="form-label margin-bottom-xxs" for="contactEmail">Email</label>
            <input class="form-control width-100%" type="email" name="contactEmail" id="contactEmail">
          </div>
      
          <div class="margin-bottom-sm">
            <label class="form-label margin-bottom-xxs" for="contactMessage">Message</label>
            <textarea class="form-control width-100%" rows="9" name="contactMessage" id="contactMessage"></textarea>
          </div>
        
          <div class="text-right">
            <button class="btn btn--primary">Submit</button>
          </div>
        </form>
      </div>
    </div>
  </div>

</section>



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
.contact-v3 {
  position: relative;
  z-index: 1;
}



</style>



