<template>
    <div class="body-content profile-product-page">
      
<section class="product-v3 padding-y-lg js-product-v3">
  <div class="container max-width-adaptive-lg">
    <div class="margin-bottom-sm">
      <nav class="breadcrumbs text-sm" aria-label="Breadcrumbs">
        <ol class="flex flex-wrap gap-xxs">
          <li class="breadcrumbs__item">
            <a href="/shop" class="color-inherit">Shop</a>
            <span class="color-contrast-low margin-left-xxs" aria-hidden="true">/</span>
          </li>
 
    
          <li class="breadcrumbs__item" aria-current="page">Tee Name</li>
        </ol>
      </nav>
    </div>
  
    <div class="grid gap-md">
      <div class="col-6@md col-7@lg">
        <div class="flex flex-column gap-sm">
          <figure>
            <img class="block width-100%" src="./../../assets/images/filter-product-gallery-img-6.jpg" alt="Image description">
          </figure>
  
          <figure>
            <img class="block width-100%" src="./../../assets/images/filter-product-gallery-img-3.jpg" alt="Image description">
          </figure>
  
          <figure>
            <img class="block width-100%" src="./../../assets/images/filter-product-gallery-img-2.jpg" alt="Image description">
          </figure>
        </div>
      </div>
  
      <div class="col-6@md col-5@lg">
        <div class="product-v3__panel">
          <div class="margin-bottom-xs">
            <h1>Product Name</h1>
          </div>
    
          <div class="flex items-center margin-bottom-sm">
            <div class="rating rating--read-only js-rating js-rating--read-only text-xs">
              <p class="sr-only">The rating of this product is <span class="rating__value js-rating__value">4.5</span> out of 5</p>
  
              <div class="rating__control rating__control--is-hidden js-rating__control">
                <svg width="24" height="24" viewBox="0 0 24 24"><polygon points="12 1.489 15.09 7.751 22 8.755 17 13.629 18.18 20.511 12 17.261 5.82 20.511 7 13.629 2 8.755 8.91 7.751 12 1.489" fill="currentColor"/></svg>
              </div>
            </div>
    
            <p class="margin-left-xxs">
              <a href="#0" class="text-sm color-inherit">65 reviews</a>
            </p>
          </div>
    
          <div class="text-component margin-bottom-lg">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo repudiandae sapiente eaque!</p>
          </div>
          
<form>
                <div class="ddf margin-bottom-lg">
                  <div class="ddf__area padding-y-xl padding-x-md js-ddf__area">
                    <input class="ddf__input sr-only js-ddf__input" type="file" id="upload-file" multiple name="file[]">

                    <label class="ddf__label js-ddf__label" for="upload-file">
                      <i class="ddf__label-inner">
                        <svg class="icon icon--xl color-contrast-higher ddf__icon-cloud" viewBox="0 0 64 64" aria-hidden="true"><path fill="currentColor" d="M51,27c-.374,0-.742.025-1.109.056a18,18,0,0,0-35.782,0C13.742,27.025,13.374,27,13,27a13,13,0,0,0,0,26H51a13,13,0,0,0,0-26Z"/><path d="M43.764,41.354l-11-13a1.033,1.033,0,0,0-1.526,0l-11,13A1,1,0,0,0,21,43h7V59h8V43h7a1,1,0,0,0,.764-1.646Z" fill="var(--color-bg)"/></svg>
                  
                        <span class="text-md text-bold color-contrast-higher">Drag and drop your files here</span>
                  
                        <span class="color-contrast-medium padding-top-xxxs inline-block">or click to browse your files</span>
                      </i>
                    </label>

                    <span class="ddf__label-end">
                      <i class="ddf__label-end-inner">
                        <svg class="icon icon--xl color-contrast-higher ddf__icon-file" viewBox="0 0 64 64" aria-hidden="true"><path fill="currentColor" d="M1.4,16.868,7,15.636,18.972,13A1.783,1.783,0,0,1,21.1,14.359L28.21,46.683a1.783,1.783,0,0,1-1.358,2.124L9.28,52.675a1.784,1.784,0,0,1-2.124-1.358L.042,18.993A1.783,1.783,0,0,1,1.4,16.868Z" opacity="0.69"/><path fill="currentColor" d="M62.6,16.868,57,15.636,45.028,13A1.783,1.783,0,0,0,42.9,14.359L35.79,46.683a1.783,1.783,0,0,0,1.358,2.124L54.72,52.675a1.784,1.784,0,0,0,2.124-1.358l7.114-32.324A1.783,1.783,0,0,0,62.6,16.868Z" opacity="0.69"/><rect fill="currentColor" x="13" y="9" width="38" height="46" rx="2"/><path d="M42.941,41.664l-5-14a1,1,0,0,0-1.624-.4l-15,14A1,1,0,0,0,22,43H42a1,1,0,0,0,.941-1.336Z" fill="#fff"/><circle cx="24" cy="26" r="3" fill="var(--color-bg)"/></svg>

                        <!-- {n} will be replaced by the total number of files -->
                        <!-- use % symbol for singular/plural - only one will be shown  -->
                        <span class="js-ddf__files-counter">{n} selected %file%files%</span>
                      </i>
                    </span>
                  </div>

                  <ul class="ddf__list is-hidden margin-top-sm js-ddf__list">
                    <li class="ddf__item js-ddf__item">
                      <div class="ddf__progress margin-right-xxs c-progress-bar js-ddf__progress" data-progress="0%">
                        <p class="sr-only" aria-live="polite" aria-atomic="true">Progress value is <span class="js-c-progress-bar__aria-value">0%</span></p>

                        <div class="c-progress-bar__shape" aria-hidden="true">
                          <svg viewBox="0 0 24 24" stroke-width="6" fill="none" stroke="currentColor" stroke-linecap="round">
                            <g> <!-- check + circle bg -->
                              <circle class="ddf__progress-circle" cx="12" cy="12" r="11" stroke-width="2"></circle>
                              <circle class="ddf__progress-circle-mask" cx="12" cy="12" r="11" stroke-width="2"></circle>
                              <polyline class="ddf__progress-check" points="6 12 10 16 18 8" fill="none" stroke="red" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"/>
                            </g>

                            <g> <!-- progress loader -->
                              <circle class="c-progress-bar__bg" cx="12" cy="12" r="11" stroke-width="2"></circle>
                              <circle class="c-progress-bar__fill" cx="12" cy="12" r="11" stroke-width="2"></circle>
                            </g>
                          </svg>
                        </div>
                      </div>

                      <span class="ddf__file-name truncate js-ddf__file-name"><!-- file name created in JS --></span>

                      <button class="reset ddf__remove-btn js-ddf__remove-btn">
                        <svg class="icon icon--xxs" viewBox="0 0 12 12"><title>Remove File</title><g stroke-width="1" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><line x1="1.5" y1="1.5" x2="10.5" y2="10.5"></line><line x1="10.5" y1="1.5" x2="1.5" y2="10.5"></line></g></svg>
                      </button>
                    </li>
                  </ul>
                </div>
                <fieldset class="margin-bottom-md">
                  <legend class="form-legend">Form Legend</legend>

                  <div class="grid gap-sm">
                    <div class="col-12@md">
                      <label class="form-label margin-bottom-xxs" for="inputName">Name</label>
                      <input class="form-control width-100%" type="text" name="inputName" id="inputName" required>
                                         <div role="alert" class="form-error-msg form-error-msg--is-visible"><p><strong>Error:</strong> this is an error message</p></div>

                    </div>
                
                 
  
                  </div>
                </fieldset>
              </form>
          <div class="flex flex-wrap gap-md js-product-v3__cta ">
            <div>
              <label class="sr-only" for="product-qty-input">Quantity:</label>

              <div class="number-input number-input--v2  js-number-input">
                <input class="form-control js-number-input__value js-product-v3__input" type="number" name="product-qty-input" id="product-qty-input" min="0" max="10" step="1" value="1">
  
                <button class="reset number-input__btn number-input__btn--plus js-number-input__btn" aria-label="Increase Number">
                  <svg class="icon" viewBox="0 0 12 12" aria-hidden="true"><path d="M11,5H7V1A1,1,0,0,0,5,1V5H1A1,1,0,0,0,1,7H5v4a1,1,0,0,0,2,0V7h4a1,1,0,0,0,0-2Z" /></svg>
                </button>

                <button class="reset number-input__btn number-input__btn--minus js-number-input__btn" aria-label="Decrease Number">
                  <svg class="icon" viewBox="0 0 12 12" aria-hidden="true"><path d="M11,7H1A1,1,0,0,1,1,5H11a1,1,0,0,1,0,2Z"/></svg>
                </button>
              </div>
            </div>
    
            <a href="/shop/profile/personalize-book" class="btn btn--primary flex-grow">Add to Cart - $49</a>
          </div>
          
        </div>
  
      
        
      </div>
    </div>
  </div>
</section>



    </div>
</template>

<script>

import { ratingJS } from './../../plugins/rating.js'
import { numberinputJS } from './../../plugins/numberinput.js'
import { loaderJS } from './../../plugins/loader.js'
import { dragdropJS } from './../../plugins/dragdropfile.js'

export default {
  mounted(){
    ratingJS();
    numberinputJS();
      dragdropJS()
    loaderJS();
  },
  destroyed() { // remove the JS code once the component has been destroyed
    ratingJS();
    numberinputJS();
        dragdropJS();
            loaderJS();
    }
}
</script>

<style lang="scss">

.product-v3__panel {
  position: sticky;
  top: var(--space-md);
}

.product-v3__cta-clone { // CTA clone visible on smaller screens
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  padding: var(--space-sm) var(--space-md);

  backdrop-filter: blur(5px);
  box-shadow: var(--shadow-lg);
  z-index: var(--zindex-fixed-element);
  transform: translateY(100%);
  visibility: hidden;
  transition: transform .3s, visibility 0s 0.3s;
}

.product-v3__cta-clone--is-visible {
  transform: translateY(0);
  visibility: visible;
  transition: transform .3s;
}

</style>



