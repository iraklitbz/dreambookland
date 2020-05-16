<template>
<div class="body-content cart-page">
 <section class="cart">
  <div class="container max-width-adaptive-lg padding-y-lg">
    <div class="margin-bottom-lg text-center">
      <h1>Your Cart</h1>
    </div>
  
    <div class="grid gap-md">
      <div class="col-8@md">
        <!-- cart products 👇 -->
        <ol class="margin-bottom-md" aria-label="Products in your cart">
          <li class="cart__product flex padding-y-sm">
            <div class="cart__product-img margin-right-sm">
              <a href="#0" class="radius-md shadow-md"><img src="../../assets/images/filter-product-gallery-img-2.jpg" alt="Image description"></a>
            </div>
      
            <div class="cart__product-info">
              <div class="text-component v-space-sm">
                <h2 class="text-md"><a href="#0" class="color-inherit">Product One</a></h2>
                <p class="text-sm color-contrast-medium">Color: Black, Size: M</p>
              </div>
    
              <div class="cart__product-tot">
                <div class="select cart__select">
                  <select class="select__input form-control" name="select-product-qty-1" id="select-product-qty-1" data-label="Select product quantity">
                    <option value="0">1</option>
                    <option value="1">2</option>
                    <option value="2">3</option>
                  </select>
                  
                  <svg class="icon select__icon" aria-hidden="true" viewBox="0 0 16 16"><g stroke-width="1" stroke="currentColor"><polyline fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" points="15.5,4.5 8,12 0.5,4.5 "></polyline></g></svg>
                </div>  
                
                <div>
                  <p class="text-md"><span class="sr-only">Price:</span>$49.00</p>
    
                  <button class="cart__remove-btn margin-top-xxs">Remove</button>
                </div>
              </div>
            </div>
          </li>
  
          <li class="cart__product flex padding-y-sm">
            <div class="cart__product-img margin-right-sm">
              <a href="#0" class="radius-md shadow-md"><img src="../../assets/images/filter-product-gallery-img-1.jpg" alt="Image description"></a>
            </div>
      
            <div class="cart__product-info">
              <div class="text-component v-space-sm">
                <h2 class="text-md"><a href="#0" class="color-inherit">Product Two</a></h2>
                <p class="text-sm color-contrast-medium">Color: Black, Size: M</p>
              </div>
    
              <div class="cart__product-tot">
                <div class="select cart__select">
                  <select class="select__input form-control" name="select-product-qty-2" id="select-product-qty-2" data-label="Select product quantity">
                    <option value="0">1</option>
                    <option value="1">2</option>
                    <option value="2">3</option>
                  </select>
                  
                  <svg class="icon select__icon" aria-hidden="true" viewBox="0 0 16 16"><g stroke-width="1" stroke="currentColor"><polyline fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" points="15.5,4.5 8,12 0.5,4.5 "></polyline></g></svg>
                </div>  
                
                <div>
                  <p class="text-md"><span class="sr-only">Price:</span>$49.00</p>
    
                  <button class="cart__remove-btn margin-top-xxs">Remove</button>
                </div>
              </div>
            </div>
          </li>
        </ol>
  
        <!-- cart gift 👇 -->
        <div class="cart__gift bg-contrast-lower radius-md padding-md">
          <h2 class="text-md">
            <span class="flex items-center">
              <svg class="icon icon--sm margin-right-xxxs" viewBox="0 0 24 24" aria-hidden="true"><g fill="none" stroke-linecap="square" stroke-linejoin="miter" stroke-width="2" stroke="currentColor"><path d="M4,3.5A2.587,2.587,0,0,1,6.667,1C10.611,1,12,6,12,6H6.667A2.587,2.587,0,0,1,4,3.5Z"></path><path d="M17.333,6H12s1.389-5,5.333-5A2.587,2.587,0,0,1,20,3.5,2.587,2.587,0,0,1,17.333,6Z"></path><path d="M21,13v8a2,2,0,0,1-2,2H5a2,2,0,0,1-2-2V13"></path><rect x="1" y="6" width="22" height="4"></rect><line x1="12" y1="6" x2="12" y2="23"></line></g></svg>
              <span>Gift options</span>
            </span>
          </h2>
  
          <div class="margin-top-sm padding-left-md">
            <ul class="flex flex-column gap-xxxs">
              <li>
                <input class="radio" type="radio" name="gift-options" id="gift-option-none" checked>
                <label for="gift-option-none">None</label>
              </li>
      
              <li class="flex-wrap">
                <input class="radio" type="radio" name="gift-options" id="gift-option-message">
                <label for="gift-option-message">Gift Card (Free)</label>
  
                <div class="cart__gift-message">
                  <label class="form-label margin-bottom-xxs" for="gift-message-free">Message:</label>
                  <textarea class="form-control width-100%" name="gift-message-free" id="gift-message-free"></textarea>
                </div>
              </li>
      
              <li class="flex-wrap">
                <input class="radio" type="radio" name="gift-options" id="gift-option-wrap">
                <label for="gift-option-wrap">Gift Wrapping and Card ($5)</label>
  
                <div class="cart__gift-message">
                  <label class="form-label margin-bottom-xxs" for="gift-message-premium">Message:</label>
                  <textarea class="form-control width-100%" name="gift-message-premium" id="gift-message-premium"></textarea>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
  
      <div class="col-4@md">
        <!-- cart subtotal 👇 -->
        <div class="cart__subtotal">
          <p class="flex justify-between"><span>Subtotal:</span> <span>$98.00</span></p>
          <a href="/shop/checkout" class="btn btn--primary btn--md width-100% margin-y-xs">Checkout &rarr;</a>
          <p class="color-contrast-medium text-sm text-center display@md">Shipping &amp; taxes calculated at checkout</p>
        </div>
      </div>
    </div>
  </div>
</section>
</div>
</template>

<script>

import { customselectJS } from './../../plugins/customselect.js'


export default {
  mounted(){
  customselectJS();
  },
  destroyed() { // remove the JS code once the component has been destroyed
  customselectJS();
    }
}
</script>

<style lang="scss">


</style>



