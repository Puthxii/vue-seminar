<template>
  <div class="section section-cards">
    <div class="container">
        <h3 class="title text-danger is-3-desktop is-3-tablet is-size-4-mobile">
          Our Best Sellers!
        </h3>
      <p class="subtitle"></p>
      <div class="row">
          <div class="col-md-10 ml-auto col-xl-3 mr-auto">
           <card style="width: 20rem;">
              <img slot="image" class="card-img-top" img src="https://images.snpfood.com/image/upload/c_fill,h_300,q_auto,w_485/v1/brands/15/inventory/products/16223--9Vvh44" alt="Card image cap">
              <div>
                <h5 class="card-title">Quinoa Fried Rice w/ Steamed Jumbo Seabass in Lime &amp; Chilli Dressing</h5>
                <p class="card-text">Nourishing Quinoa Fried Rice. Serve with Steamed Giant Seabass and spicy seafood sauce.</p>
                245<span class="price-symbol" >฿</span>
                <n-button type="danger">Add to Cart</n-button>
              </div>
            </card>
        </div>
 
          <div class="col-md-10 ml-auto col-xl-3 mr-auto">
          <card style="width: 20rem;">
              <img slot="image" class="card-img-top" img src="https://images.snpfood.com/image/upload/c_fill,h_300,q_auto,w_485/v1/brands/15/inventory/products/18919--fT4VOB" alt="Card image cap">
              <div>
               <h5 class="card-title">Roast Chicken Salad</h5>
                <p class="card-text">Organic salad vegetables are grown in non-toxic farms. They are fresh and ready for cook every day.</p>
                215<span class="price-symbol" >฿</span>
                <n-button type="danger">Add to Cart</n-button>
              </div>
            </card>
        </div>
    
          <div class="col-md-10 ml-auto col-xl-3 mr-auto">
          <card style="width: 20rem;">
            <img slot="image" class="card-img-top" img src="https://images.snpfood.com/image/upload/c_fill,h_300,q_auto,w_485/v1/brands/15/inventory/products/16259--L0wIOW" alt="Card image cap">
            <div>
              <h5 class="card-title">Fried Rice Vermicelli Thai Style w/ Prawns</h5>
                <p class="card-text">Top Recommended! Unique Thai noodle from Nonthaburi. Serve with Padthai traditional sauce. With the additional fresh prawns.</p>
                145<span class="price-symbol" >฿</span>
                <n-button type="danger">Add to Cart</n-button>
            </div>
          </card>
        </div>
     
            <div class="col-md-10 ml-auto col-xl-3 mr-auto">
            <card style="width: 20rem;">
              <img slot="image" class="card-img-top" img src="https://images.snpfood.com/image/upload/c_fill,h_300,q_auto,w_485/v1/brands/15/inventory/products/24878--kFd3xN" alt="Card image cap">
              <div>
               <h5 class="card-title">Strawberry Jelio Smoothie</h5>
                <p class="card-text">Strawberry Jelio Smoothie.</p>
                128<span class="price-symbol" >฿</span>
                <n-button type="danger">Add to Cart</n-button>
              </div>
            </card>
        </div>
  
      </div>
    </div>
  </div>
</template>
<script>
import { Card, Tabs, TabPane, Button} from '@/components';

export default {
  components: {
    Card,
    Tabs,
    TabPane,
    [Button.name]: Button,
  }
};
</script>
<style>

</style>


