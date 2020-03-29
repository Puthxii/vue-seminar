<template>
  <div class="section" id="carousel">
    <div class="container-fluid">
    
      <div class="row justify-content-center d-none d-md-block">
        <div class="col-12">
          <el-carousel height="630px">
            <el-carousel-item>
              <img class="d-block" src="img/nbg1.jpg" alt="First slide" />
              <div class="carousel-caption d-none d-md-block">
                <h5>Nature, United States</h5>
              </div>
            </el-carousel-item>
            <el-carousel-item>
              <img class="d-block" src="img/nbg2.jpg" alt="Second slide" />
              <div class="carousel-caption d-none d-md-block">
                <h5>Somewhere Beyond, United States</h5>
              </div>
            </el-carousel-item>
            <el-carousel-item>
              <img class="d-block" src="img/nbg3.jpg" alt="Third slide" />
              <div class="carousel-caption d-none d-md-block">
                <h5>Yellowstone National Park, United States</h5>
              </div>
            </el-carousel-item>
            <el-carousel-item>
              <img class="d-block" src="img/nbg4.jpg" alt="fourth slide" />
              <div class="carousel-caption d-none d-md-block">
                <h5>Yellowstone National Park, United States</h5>
              </div>
            </el-carousel-item>
          </el-carousel>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { Carousel, CarouselItem } from 'element-ui';

export default {
  components: {
    [Carousel.name]: Carousel,
    [CarouselItem.name]: CarouselItem
  }
};
</script>
<style></style>
