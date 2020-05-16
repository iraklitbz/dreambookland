<template>
<div class="body-content shop-page">
   <section class="padding-y-xl">
  <div class="container max-width-adaptive-lg">
    <div class="margin-bottom-md">
      <h1 class="text-center">Our Products</h1>
    </div>

    <div class="filter-nav filter-nav--expanded js-filter-nav">
      <button class="reset btn btn--subtle is-hidden js-filter-nav__control" aria-label="Select a filter option" aria-controls="filter-nav">
        <span class="js-filter-nav__placeholder" aria-hidden="true">All Products</span>

        <svg class="icon icon--xxs margin-left-xxs" aria-hidden="true" viewBox="0 0 12 12"><polyline points="0.5 3.5 6 9.5 11.5 3.5" fill="none" stroke-width="1" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"></polyline></svg>
      </button>

      <div class="filter-nav__wrapper js-filter-nav__wrapper" id="filter-nav">
        <nav class="filter-nav__nav justify-center js-filter-nav__nav">
          <ul class="filter-nav__list js-filter-nav__list" aria-controls="product-gallery">
            <li class="filter-nav__item">
              <button class="reset filter-nav__btn js-filter-nav__btn js-tab-focus" aria-current="true" data-filter="*">All Products</button>
            </li>
            
            <li class="filter-nav__item">
              <button class="reset filter-nav__btn js-filter-nav__btn js-tab-focus" data-filter="coffee-mug">Coffe mugs</button>
            </li>
          
            <li class="filter-nav__item">
              <button class="reset filter-nav__btn js-filter-nav__btn js-tab-focus" data-filter="tea-mug">Tea mugs</button>
            </li>
          
            <li class="filter-nav__item">
              <button class="reset filter-nav__btn js-filter-nav__btn js-tab-focus" data-filter="other">Others</button>
            </li>
          <li class="filter-nav__marker js-filter-nav__marker" aria-hidden="true"></li>
          </ul>

          <button class="reset filter-nav__close-btn is-hidden js-filter-nav__close-btn js-tab-focus" aria-label="Close navigation">
            <svg class="icon" viewBox="0 0 16 16" aria-hidden="true"><g stroke-width="1" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10"><line x1="13.5" y1="2.5" x2="2.5" y2="13.5"></line><line x1="2.5" y1="2.5" x2="13.5" y2="13.5"></line></g></svg>
          </button>
        </nav>
      </div>
    </div>
    
    <div class="margin-top-md">
      <ul class="grid gap-sm js-filter" id="product-gallery">
        <li class="col-6@sm col-4@md js-filter__item" data-filter="coffee-mug">
          <div class="prod-card ">
            

            <a href="/shop/profile" class="prod-card__img-link" aria-label="Description of the link">
              <figure class="prod-card__img media-wrapper media-wrapper--1:1">
                <img src="./../../assets/images/filter-product-gallery-img-1.jpg" alt="Product preview image">
              </figure>
            </a>

            <div class="prod-card__content text-center">
              <h3><a href="/shop/profile">Product One</a></h3>

              <div class="margin-top-xs">
                <span class="prod-card__price">$79</span>
              </div>
            </div>
          </div>
        </li>
    
        <li class="col-6@sm col-4@md js-filter__item" data-filter="tea-mug">
          <div class="prod-card ">
            

            <a href="/shop/profile" class="prod-card__img-link" aria-label="Description of the link">
              <figure class="prod-card__img media-wrapper media-wrapper--1:1">
                <img src="./../../assets/images/filter-product-gallery-img-2.jpg" alt="Product preview image">
              </figure>
            </a>

            <div class="prod-card__content text-center">
              <h3><a href="/shop/profile">Product Two</a></h3>

              <div class="margin-top-xs">
                <span class="prod-card__price">$79</span>
              </div>
            </div>
          </div>
        </li>
    
        <li class="col-6@sm col-4@md js-filter__item" data-filter="tea-mug">
          <div class="prod-card ">
            

            <a href="/shop/profile" class="prod-card__img-link" aria-label="Description of the link">
              <figure class="prod-card__img media-wrapper media-wrapper--1:1">
                <img src="./../../assets/images/filter-product-gallery-img-3.jpg" alt="Product preview image">
              </figure>
            </a>

            <div class="prod-card__content text-center">
              <h3><a href="/shop/profile">Product Three</a></h3>

              <div class="margin-top-xs">
                <span class="prod-card__price">$79</span>
              </div>
            </div>
          </div>
        </li>
    
        <li class="col-6@sm col-4@md js-filter__item" data-filter="other">
          <div class="prod-card ">
            

            <a href="/shop/profile" class="prod-card__img-link" aria-label="Description of the link">
              <figure class="prod-card__img media-wrapper media-wrapper--1:1">
                <img src="./../../assets/images/filter-product-gallery-img-4.jpg" alt="Product preview image">
              </figure>
            </a>

            <div class="prod-card__content text-center">
              <h3><a href="/shop/profile">Product Four</a></h3>

              <div class="margin-top-xs">
                <span class="prod-card__price">$79</span>
              </div>
            </div>
          </div>
        </li>
    
        <li class="col-6@sm col-4@md js-filter__item" data-filter="coffee-mug">
          <div class="prod-card ">
            

            <a href="/shop/profile" class="prod-card__img-link" aria-label="Description of the link">
              <figure class="prod-card__img media-wrapper media-wrapper--1:1">
                <img src="./../../assets/images/filter-product-gallery-img-5.jpg" alt="Product preview image">
              </figure>
            </a>

            <div class="prod-card__content text-center">
              <h3><a href="/shop/profile">Product Five</a></h3>

              <div class="margin-top-xs">
                <span class="prod-card__price">$79</span>
              </div>
            </div>
          </div>
        </li>
    
        <li class="col-6@sm col-4@md js-filter__item" data-filter="tea-mug">
          <div class="prod-card ">
            

            <a href="/shop/profile" class="prod-card__img-link" aria-label="Description of the link">
              <figure class="prod-card__img media-wrapper media-wrapper--1:1">
                <img src="./../../assets/images/filter-product-gallery-img-6.jpg" alt="Product preview image">
              </figure>
            </a>

            <div class="prod-card__content text-center">
              <h3><a href="/shop/profile">Product Six</a></h3>

              <div class="margin-top-xs">
                <span class="prod-card__price">$79</span>
              </div>
            </div>
          </div>
        </li>
      </ul>
    </div>
  </div>
</section>
</div>
</template>

<script>

import { filterJS } from './../../plugins/filter.js'
import { filternavJS } from './../../plugins/filternav.js'


export default {
  mounted(){
  filterJS();
  filternavJS()
  },
  destroyed() { // remove the JS code once the component has been destroyed
  filterJS();
  filternavJS()
    }
}
</script>

<style lang="scss">


</style>



