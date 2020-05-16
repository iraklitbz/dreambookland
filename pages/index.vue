<template>
  <div class="body-content">

<section class="bg-contrast-lower padding-y-xxl position-relative z-index-1">
  <div class="container max-width-adaptive-lg position-relative z-index-2">
    <div class="text-sm opacity-60% margin-bottom-xxs">This is a Label</div>

    <div class="text-component margin-bottom-sm">
      <h1>Lorem ipsum dolor sit amet consectetur adipisicing elit</h1>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam vero aliquam, natus quae architecto hic quod!
      </p>
    </div>

    <div class="flex flex-wrap items-center gap-sm">
      <a href="#0" class="btn btn--primary">Download</a>
      <a href="#0" class="color-inherit">Learn more</a>
    </div>
  </div>

  <figure class="bg-decoration-v2 z-index-1 flip-y" aria-hidden="true">
    <svg class="bg-decoration-v2__svg color-contrast-higher opacity-10%" viewBox="0 0 1920 450" fill="none">
      <g stroke="currentColor" stroke-width="2">
        <rect width="212" height="212" transform="matrix(1 0 0 -1 1506 186)" />
        <circle r="106" transform="matrix(1 0 0 -1 1506 186)" />
        <path d="M1335 45C1335 34.5066 1343.51 26 1354 26C1364.49 26 1373 34.5066 1373 45C1373 55.4934 1364.49 64 1354 64" />
        <path d="M1506 186L1718 -26" />
      </g>
    </svg>
  </figure>
</section>

  <section class="gallery-v2 padding-y-xl">
  <div class="container max-width-adaptive-lg clearfix">
    <div class="margin-bottom-xl clearfix">
      <div class="grid gap-sm">
        <div class="">
          <div class="text-component line-height-lg">
            <h1>Build & Deploy</h1>

            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque sed tenetur rem quam nihil dolorum expedita maxime nisi recusandae sequi magni culpa fuga accusamus eveniet fugiat ipsum ab consequuntur.</p>

            <p class="text-right"><a class="btn btn--subtle" href="#0">Read more</a></p>
          </div>
        </div>
      </div>
    </div>

    <ul class="gallery-v2__grid grid gap-sm">
      <li class="gallery-v2__item col-6@sm col-3@lg">

        <div class="card-v2 radius-md">
          <figure>
            <img src="../assets/images/filter-product-gallery-img-4.jpg" alt="Image description">
            <figcaption class="card-v2__caption padding-x-sm padding-top-md padding-bottom-sm text-center">
              <div class="text-md text-base@md">Card Title</div>
              <div class="margin-top-xxxs text-sm opacity-70%">Label</div>
            </figcaption>
          </figure>
        </div>
      </li>

      <li class="gallery-v2__item col-6@sm col-3@lg">

        <div class="card-v2 radius-md">
          <figure>
            <img src="../assets/images/filter-product-gallery-img-3.jpg" alt="Image description">
            <figcaption class="card-v2__caption padding-x-sm padding-top-md padding-bottom-sm text-center">
              <div class="text-md text-base@md">Card Title</div>
              <div class="margin-top-xxxs text-sm opacity-70%">Label</div>
            </figcaption>
          </figure>
        </div>
      </li>

      <li class="gallery-v2__item col-6@sm col-3@lg">

        <div class="card-v2 radius-md">
          <figure>
            <img src="../assets/images/filter-product-gallery-img-2.jpg" alt="Image description">
            <figcaption class="card-v2__caption padding-x-sm padding-top-md padding-bottom-sm text-center">
              <div class="text-md text-base@md">Card Title</div>
              <div class="margin-top-xxxs text-sm opacity-70%">Label</div>
            </figcaption>
          </figure>
        </div>
      </li>

      <li class="gallery-v2__item col-6@sm col-3@lg">

        <div class="card-v2 radius-md">
          <figure>
            <img src="../assets/images/filter-product-gallery-img-1.jpg" alt="Image description">
            <figcaption class="card-v2__caption padding-x-sm padding-top-md padding-bottom-sm text-center">
              <div class="text-md text-base@md">Card Title</div>
              <div class="margin-top-xxxs text-sm opacity-70%">Label</div>
            </figcaption>
          </figure>
        </div>
      </li>
    </ul>
  </div>
</section>



  </div>
</template>

<script>
import Header from '~/components/Header.vue'


export default {
  components: {
    Header
  },
  mounted(){
 
  },
  destroyed() { // remove the JS code once the component has been destroyed
   
    }
}
</script>

<style lang="scss">
:root {
  --gallery-v2-offset: 50px; // grid items offset value 
}


.bg-decoration-v2 {
  position: absolute;
  top: 0;
  left: 0;
  pointer-events: none;
  width: 100%;
  height: 100%;
  overflow: hidden;
}

.bg-decoration-v2__svg {
  position: absolute;
  top: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 134%;
  min-width: 1280px;
  max-width: 1920px;
  height: auto;
}


.gallery-v2 {
  position: relative;
  z-index: 1;
}

@include breakpoint(sm) {
  .gallery-v2__grid {
    padding-bottom: var(--gallery-v2-offset);
  }

  .gallery-v2__item:nth-child(2n) {
    transform: translateY(var(--gallery-v2-offset));
  }
}



</style>



