<template>
 <div class="body-content checkout-page">
<section class="checkout padding-y-xl margin-top-lg">
  <div class="container max-width-adaptive-lg">
    <div class="text-component margin-bottom-lg">
      <h1>Checkout</h1>
      <p class="text-sm@md">Already have an account? <a href="/login">Login</a></p>
    </div>

    <form>
      <div class="grid gap-md">
        <div class="col-7@lg">
          <!-- contact info -->
          <fieldset class="margin-bottom-lg">
            <legend class="form-legend font-bold">1. Contact Information</legend>
            
            <label class="form-label margin-bottom-xxs" for="checkEmail">Email</label>
            <input class="form-control width-100%" type="email" name="checkEmail" id="checkEmail" required>
          </fieldset>
    
          <!-- delivery address -->
          <fieldset class="margin-bottom-lg">
            <legend class="form-legend font-bold">2. Delivery Address</legend>
            
            <div class="grid gap-sm">
              <div class="col-6@sm">
                <label class="form-label margin-bottom-xxs" for="checkDeliveryName">Full Name</label>
                <input class="form-control width-100%" type="text" name="checkDeliveryName" id="checkDeliveryName" required>
              </div>
      
              <div class="col-6@sm">
                <label class="form-label margin-bottom-xxs" for="checkDeliveryCompany">Company (optional)</label>
                <input class="form-control width-100%" type="text" name="checkDeliveryCompany" id="checkDeliveryCompany">
              </div>
      
              <div>
                <label class="form-label margin-bottom-xxs" for="checkDeliveryAddress">Address</label>
                <input class="form-control width-100%" type="text" name="checkDeliveryAddress" id="checkDeliveryAddress" required>
              </div>
      
              <div class="col-6@sm">
                <label class="form-label margin-bottom-xxs" for="checkDeliveryCity">City</label>
                <input class="form-control width-100%" type="text" name="checkDeliveryCity" id="checkDeliveryCity" required>
              </div>
      
              <div class="col-6@sm">
                <label class="form-label margin-bottom-xxs" for="checkDeliveryState">State (optional)</label>
                <input class="form-control width-100%" type="text" name="checkDeliveryState" id="checkDeliveryState">
              </div>
      
              <div class="col-6@sm">
                <label class="form-label margin-bottom-xxs" for="checkDeliveryCountry">Country</label>

                <div class="select">
                  <select class="select__input form-control" name="checkDeliveryCountry" id="checkDeliveryCountry">
                    <option value="0">Select Country</option>
                    <option value="1">USA</option>
                    <option value="2">Italy</option>
                  </select>
                  
                  <svg class="icon select__icon" aria-hidden="true" viewBox="0 0 16 16"><g stroke-width="1" stroke="currentColor"><polyline fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" points="15.5,4.5 8,12 0.5,4.5 "></polyline></g></svg>
                </div>
              </div>
      
              <div class="col-6@sm">
                <label class="form-label margin-bottom-xxs" for="checkDeliveryPostcode">Postcode</label>
                <input class="form-control width-100%" type="text" name="checkDeliveryPostcode" id="checkDeliveryPostcode" required>
              </div>
      
              <div>
                <label class="form-label margin-bottom-xxs" for="checkDeliveryTel">Phone number (optional)</label>
                <input class="form-control width-100%" type="tel" name="checkDeliveryTel" id="checkDeliveryTel">
              </div>
            </div>
          </fieldset>
    
          <!-- delivery options -->
          <fieldset class="margin-bottom-lg">
            <legend class="form-legend font-bold">3. Delivery Options</legend>
            
            <div class="choice-btns gap-xs js-choice-btns">
              <div class="choice-btn padding-sm js-choice-btn">
                <div class="choice-btn__fallback">
                  <input type="radio" name="checkDeliveryOptions" id="checkDeliveryStandard" checked>
                  <label for="checkDeliveryStandard">Standard delivery, 4-5 days, $9.00</label>
                </div>

                <div class="choice-btn__grid" aria-hidden="true">
                  <div class="choice-btn__input choice-btn__input--radio">
                    <svg class="icon" viewBox="0 0 16 16"><circle fill="currentColor" cx="8" cy="8" r="4"/></svg>
                  </div>

                  <div class="flex flex-wrap gap-xs justify-between">
                    <div>
                      <p class="color-contrast-higher ">Standard delivery</p>
                      <p class="color-contrast-medium text-sm">4-5 days</p>
                    </div>
  
                    <p class="color-contrast-higher ">$9.00</p>
                  </div>
                </div>
              </div>
  
              <div class="choice-btn padding-sm js-choice-btn">
                <div class="choice-btn__fallback">
                  <input type="radio" name="checkDeliveryOptions" id="checkDeliveryExpress" null>
                  <label for="checkDeliveryExpress">Express delivery, 1-2 days, $19.00</label>
                </div>

                <div class="choice-btn__grid" aria-hidden="true">
                  <div class="choice-btn__input choice-btn__input--radio">
                    <svg class="icon" viewBox="0 0 16 16"><circle fill="currentColor" cx="8" cy="8" r="4"/></svg>
                  </div>

                  <div class="flex flex-wrap gap-xs justify-between">
                    <div>
                      <p class="color-contrast-higher ">Express delivery</p>
                      <p class="color-contrast-medium text-sm">1-2 days</p>
                    </div>
  
                    <p class="color-contrast-higher ">$19.00</p>
                  </div>
                </div>
              </div>
  
              
            </div>
          </fieldset>
    
          <!-- billing address -->
          <fieldset class="margin-bottom-lg">
            <legend class="form-legend font-bold">4. Billing Address</legend>

            <div class="checkout__billing-checkbox">
              <div>
                <input class="checkbox js-billing-checkbox" type="checkbox" id="autofillBillingInfo" checked>
                <label for="autofillBillingInfo">Same as delivery address</label>
              </div>
            </div>

            <div class="checkout__billing-info margin-top-md js-billing-info">
              <div class="grid gap-sm">
                <div class="col-6@sm">
                  <label class="form-label margin-bottom-xxs" for="checkBillingName">Full Name</label>
                  <input class="form-control width-100%" type="text" name="checkBillingName" id="checkBillingName" required>
                </div>
        
                <div class="col-6@sm">
                  <label class="form-label margin-bottom-xxs" for="checkBillingCompany">Company (optional)</label>
                  <input class="form-control width-100%" type="text" name="checkBillingCompany" id="checkBillingCompany">
                </div>
        
                <div>
                  <label class="form-label margin-bottom-xxs" for="checkBillingAddress">Address</label>
                  <input class="form-control width-100%" type="text" name="checkBillingAddress" id="checkBillingAddress" required>
                </div>
        
                <div class="col-6@sm">
                  <label class="form-label margin-bottom-xxs" for="checkBillingCity">City</label>
                  <input class="form-control width-100%" type="text" name="checkBillingCity" id="checkBillingCity" required>
                </div>
        
                <div class="col-6@sm">
                  <label class="form-label margin-bottom-xxs" for="checkBillingState">State (optional)</label>
                  <input class="form-control width-100%" type="text" name="checkBillingState" id="checkBillingState">
                </div>
        
                <div class="col-6@sm">
                  <label class="form-label margin-bottom-xxs" for="checkBillingCountry">Country</label>
  
                  <div class="select">
                    <select class="select__input form-control" name="checkBillingCountry" id="checkBillingCountry">
                      <option value="0">Select Country</option>
                      <option value="1">USA</option>
                      <option value="2">Italy</option>
                    </select>
                    
                    <svg class="icon select__icon" aria-hidden="true" viewBox="0 0 16 16"><g stroke-width="1" stroke="currentColor"><polyline fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" points="15.5,4.5 8,12 0.5,4.5 "></polyline></g></svg>
                  </div>
                </div>
        
                <div class="col-6@sm">
                  <label class="form-label margin-bottom-xxs" for="checkBillingPostcode">Postcode</label>
                  <input class="form-control width-100%" type="text" name="checkBillingPostcode" id="checkBillingPostcode" required>
                </div>
              </div>
            </div>
          </fieldset>
    
          <!-- payment method -->
          <fieldset class="margin-bottom-lg@lg">
            <legend class="form-legend font-bold">5. Payment Method</legend>
    
            <div class="choice-accordion js-choice-accordion" data-animation="on">
              <div class="choice-accordion__item">
                <div class="choice-accordion__fallback js-choice-accordion__fallback">
                  <input type="radio" name="checkPayMethod" id="checkPayCard" checked>
                  <label for="checkPayCard">Credit Card</label>
                </div>
            
                <div class="choice-accordion__btn padding-sm js-choice-accordion__btn" aria-hidden="true">
                  <div class="choice-accordion__input choice-accordion__input--radio">
                    <svg class="icon" viewBox="0 0 16 16"><circle fill="currentColor" cx="8" cy="8" r="4"/></svg>
                  </div>
            
                  <p class="color-contrast-higher">Credit Card</p>
                </div>
            
                <div class="choice-accordion__panel js-choice-accordion__panel">
                  <div class="grid gap-sm padding-sm">
                    <div>
                      <label class="form-label margin-bottom-xxs" for="checkCardNumber">Card Number</label>
                      <input class="form-control width-100%" type="text" name="checkCardNumber" id="checkCardNumber" required>
                    </div>

                    <div>
                      <label class="form-label margin-bottom-xxs" for="checkCardName">Name on Card</label>
                      <input class="form-control width-100%" type="text" name="checkCardName" id="checkCardName" required>
                    </div>

                    <div class="col-6@sm">
                      <label class="form-label margin-bottom-xxs" for="checkCardExpiration">Expiration date (MM/YY)</label>
                      <input class="form-control width-100%" type="text" name="checkCardExpiration" id="checkCardExpiration" required>
                    </div>

                    <div class="col-6@sm">
                      <label class="form-label margin-bottom-xxs" for="checkCardSecCode">Security code</label>
                      <input class="form-control width-100%" type="text" name="checkCardSecCode" id="checkCardSecCode" required>
                    </div>
                  </div>
                </div>
              </div>
            
              <div class="choice-accordion__item">
                <div class="choice-accordion__fallback js-choice-accordion__fallback">
                  <input type="radio" name="checkPayMethod" id="checkPayPaypal">
                  <label for="checkPayPaypal">Paypal</label>
                </div>
            
                <div class="choice-accordion__btn padding-sm js-choice-accordion__btn" aria-hidden="true">
                  <div class="choice-accordion__input choice-accordion__input--radio">
                    <svg class="icon" viewBox="0 0 16 16"><circle fill="currentColor" cx="8" cy="8" r="4"/></svg>
                  </div>
            
                  <svg class="icon width-auto color-contrast-higher" viewBox="0 0 287 78"><path fill="currentColor" d="M193.628.776h-22.251a3.091 3.091 0 00-3.053 2.61l-9 57.053a1.855 1.855 0 001.832 2.144h11.417a2.163 2.163 0 002.137-1.827l2.552-16.174a3.091 3.091 0 013.054-2.61h7.041c14.655 0 23.113-7.093 25.324-21.15 1-6.148.04-10.979-2.839-14.361-3.162-3.719-8.77-5.685-16.214-5.685zm2.572 20.837c-1.22 7.987-7.319 7.987-13.22 7.987h-3.356l2.354-14.912a1.856 1.856 0 011.832-1.566h1.539c4.016 0 7.81 0 9.765 2.288 1.171 1.37 1.524 3.399 1.086 6.203zM34.932.776h-22.25a3.093 3.093 0 00-3.054 2.61l-9 57.053a1.856 1.856 0 001.833 2.144h10.626a3.092 3.092 0 003.054-2.609l2.428-15.392a3.091 3.091 0 013.053-2.61h7.041c14.656 0 23.114-7.093 25.325-21.15.995-6.148.04-10.979-2.838-14.361C47.984 2.742 42.375.776 34.932.776zM37.5 21.613C36.284 29.6 30.184 29.6 24.285 29.6h-3.357l2.354-14.912a1.855 1.855 0 011.832-1.566h1.539c4.016 0 7.81 0 9.765 2.288 1.17 1.37 1.524 3.399 1.082 6.203zM101.435 21.358H90.782a1.856 1.856 0 00-1.833 1.566l-.468 2.976-.745-1.079c-2.308-3.349-7.45-4.468-12.585-4.468-11.77 0-21.826 8.92-23.783 21.43-1.019 6.241.427 12.206 3.966 16.369 3.251 3.825 7.891 5.417 13.419 5.417a20.4 20.4 0 0014.75-6.1l-.476 2.962a1.854 1.854 0 001.832 2.145h9.595a3.091 3.091 0 003.053-2.608l5.76-36.473a1.854 1.854 0 00-1.832-2.137zM86.587 42.1a11.879 11.879 0 01-12.026 10.17 8.992 8.992 0 01-7.154-2.876 9.048 9.048 0 01-1.669-7.483 11.924 11.924 0 0111.94-10.252 8.975 8.975 0 017.1 2.9 9.176 9.176 0 011.809 7.541zM260.131 21.358h-10.653a1.854 1.854 0 00-1.832 1.566l-.469 2.979-.745-1.079c-2.308-3.349-7.45-4.468-12.585-4.468-11.771 0-21.826 8.92-23.782 21.43-1.019 6.241.427 12.206 3.966 16.369 3.251 3.825 7.891 5.417 13.419 5.417a20.4 20.4 0 0014.75-6.1l-.476 2.962a1.854 1.854 0 001.832 2.145h9.595a3.091 3.091 0 003.053-2.608l5.76-36.473a1.855 1.855 0 00-1.833-2.14zM245.284 42.1a11.878 11.878 0 01-12.025 10.17 8.994 8.994 0 01-7.155-2.876 9.052 9.052 0 01-1.669-7.483 11.923 11.923 0 0111.939-10.252 8.979 8.979 0 017.1 2.9 9.183 9.183 0 011.81 7.541zM158.181 21.358h-10.709a3.1 3.1 0 00-2.558 1.356L130.142 44.47l-6.261-20.907a3.093 3.093 0 00-2.961-2.206h-10.527a1.856 1.856 0 00-1.756 2.454l11.792 34.612-11.091 15.648A1.855 1.855 0 00110.852 77h10.7a3.091 3.091 0 002.541-1.331l35.614-51.4a1.855 1.855 0 00-1.526-2.911zM272.69 2.343l-9.133 58.1a1.855 1.855 0 001.832 2.143h9.185a3.092 3.092 0 003.054-2.609l9-57.053A1.854 1.854 0 00284.8.777h-10.277a1.854 1.854 0 00-1.833 1.566z"/></svg>
                </div>
              </div>
            </div>
          </fieldset>
    
          <button class="btn btn--primary btn--md width-100% display@lg">Place Order</button>
        </div>

        <div class="col-5@lg">
          <!-- order summary -->
          <aside class="order-summary bg-contrast-lower radius-md">
            <header class="order-summary__header bg-contrast-lower flex justify-between padding-sm">
              <p>Your cart (2) <span class="sr-only">items</span></p>
              <a href="/shop/cart" class="text-sm" role="text">Edit <i class="sr-only">cart</i></a>
            </header>
          
            <div class="padding-x-sm">
              <ul class="flex flex-column gap-sm">
                <li class="order-summary__item">
                  <a href="#0" class="order-summary__img"><img src="../../../assets/images/filter-product-gallery-img-2.jpg" alt="Image description"></a>
            
                  <div class="flex flex-wrap justify-between gap-xxxs">
                    <div>
                      <p class="color-contrast-higher font-bold">Product One</p>
                      <p class="color-contrast-medium text-sm">Color: Black, Size: M, Qty: 1</p>
                    </div>
                    
                    <p class="color-contrast-higher font-bold"><span class="sr-only">Price:</span> $49.00</p>
                  </div>
                </li>
            
                <li class="order-summary__item">
                  <a href="#0" class="order-summary__img"><img src="../../../assets/images/filter-product-gallery-img-1.jpg" alt="Image description"></a>
            
                  <div class="flex flex-wrap justify-between gap-xxxs">
                    <div>
                      <p class="color-contrast-higher font-bold">Product Two</p>
                      <p class="color-contrast-medium text-sm">Color: Black, Size: M, Qty: 1</p>
                    </div>
                    
                    <p class="color-contrast-higher font-bold"><span class="sr-only">Price:</span> $49.00</p>
                  </div>
                </li>
              </ul>
            </div>
          
            <footer class="order-summary__footer bg-contrast-lower padding-x-sm padding-bottom-sm">
              <div class="margin-y-sm padding-y-sm border-top border-bottom">
                <div class="flex flex-column flex-row@md gap-xxs">
                  <input aria-label="Discount code" class="form-control flex-grow min-width-0" type="email" placeholder="Discount code">
                  <button class="btn btn--primary">Apply</button>
                </div>
              </div>
            
              <ul class="flex flex-column gap-xxs">
                <li class="flex justify-between"><i>Subtotal</i> <i>$98.00</i></li>
                <li class="flex justify-between"><i>Tax</i> <i>$10.00</i></li>
                <li class="flex justify-between"><i>Delivery</i> <i>Free</i></li>
                <li class="flex justify-between font-bold"><i>Total</i> <i>$108.00</i></li>
              </ul>
            </footer>
          </aside>
        </div>
      </div>

      <button class="btn btn--primary btn--lg width-100% hide@lg margin-top-md">Place Order</button>
    </form>
  </div>
</section>
 </div>
</template>

<script>

import { customselectJS } from './../../../plugins/customselect.js'
import { choisebuttonsJS } from './../../../plugins/choisebutton.js'
import { acordionJS } from './../../../plugins/acordion.js'


export default {
  mounted(){
  customselectJS();
  choisebuttonsJS()
  acordionJS();
        (function() {
        // update billing info visibility
        var billingCheckBox = document.getElementsByClassName('js-billing-checkbox');
        if(billingCheckBox.length > 0) {
            var billingInfo = document.getElementsByClassName('js-billing-info');
            if(billingInfo.length == 0) return;
            resetBillingInfo(billingCheckBox[0], billingInfo[0]);
            
            billingCheckBox[0].addEventListener('change', function(){
            resetBillingInfo(billingCheckBox[0], billingInfo[0]);
            });
        }

        function resetBillingInfo(input, content) {
            Util.toggleClass(content, 'is-visible', !input.checked);
        };
        }());
  },
  destroyed() { // remove the JS code once the component has been destroyed
    customselectJS();
    choisebuttonsJS();
    acordionJS()
    }
}
</script>

<style lang="scss">
:root {
  --order-summary-img-size: 3.6em;
  --order-summary-img-margin-right: var(--space-xs);
}

.order-summary {}

.order-summary__header {
  border-radius: inherit;
  border-bottom-left-radius: 0px;
  border-bottom-right-radius: 0px;
}

.order-summary__footer {
  border-radius: inherit;
  border-top-left-radius: 0px;
  border-top-right-radius: 0px;
}

.order-summary__item {
  display: grid;
  grid-template-columns: var(--order-summary-img-size) 1fr;
  grid-gap: var(--order-summary-img-margin-right);
  align-items: center;
}

.order-summary__img {
  display: block;
  width: var(--order-summary-img-size);
  height: var(--order-summary-img-size);
  border-radius: var(--radius-md);
  overflow: hidden;
  box-shadow: var(--shadow-sm);
  transition: .2s;

  img {
    display: block;
    width: 100%;
    object-fit: cover;
  }

  &:hover {
    transform: translateY(-1px);
    box-shadow: var(--shadow-sm);
  }
}

</style>



