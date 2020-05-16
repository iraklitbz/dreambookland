<template>
 <div class="body-content thanks-page">


<section class="thank-you padding-y-xxl">
  <div class="container max-width-adaptive-sm text-center">
    <svg class="thank-you__icon margin-bottom-sm" viewBox="0 0 80 80" aria-hidden="true"><g class="thank-you__icon-group"><circle fill="var(--color-success)" cx="40" cy="40" r="40"/><polyline points="21 41 33 53 59 27" fill="none" stroke="#fff" stroke-miterlimit="10" stroke-width="2"/></g></svg>

    <div class="text-component">
      <h1 class="text-xxxl">Order Confirmed</h1>
        <p class="color-contrast-medium">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi aliquid qui et saepe omnis ipsum amet quasi accusamus.</p>

        <p class="flex flex-wrap flex-column flex-row@xs gap-xxs justify-center">
          <a class="btn btn--subtle" href="/shop">Continue Shopping</a>
          <a class="btn btn--primary" href="#0">Manage Order</a>
        </p>
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

.thank-you {
  position: relative;
  z-index: 1;
}

.thank-you__icon {
  width: 80px; // icon size
  height: 80px; // icon size
}

.thank-you__icon-group {
  transform-origin: 50% 50%;
  animation: thank-you-icon .5s var(--ease-out);
  
  > *:last-child {
    transform-origin: 50% 50%;
    stroke-dashoffset: 55;
    stroke-dasharray: 55;
    animation: thank-you-icon-check .5s var(--ease-out) forwards;
  }
}

@keyframes thank-you-icon {
  from {
    transform: scale(0.5);
    opacity: 0;
  }
  to {
    transform: scale(1);
    opacity: 1;
  }
}

@keyframes thank-you-icon-check {
  from {
    stroke-dashoffset: 55;
  }
  to {
    stroke-dashoffset: 0;
  }
}

</style>



