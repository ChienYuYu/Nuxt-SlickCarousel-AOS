<template>
  <div class="carousel-wrap">
    <SlickCarousel v-bind="slickOptions">
      <div>
        <img
          src="https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1920&q=80">
      </div>
      <div>
        <img
          src="https://images.unsplash.com/photo-1573167507387-6b4b98cb7c13?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1920&q=80">
      </div>
      <div>
        <img
          src="https://images.unsplash.com/photo-1551135049-8a33b5883817?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1920&q=80">
      </div>
    </SlickCarousel>
  </div>
</template>

<script>
export default {
  data () {
    return {
      slickOptions: {
        dots: true,
        autoplay: true,
        autoplaySpeed: 3000,
        infinite: true,
        arows: true,
        slidesToShow: 1
      }
    }
  }
}
</script>

<style>
.carousel-wrap {
  position: relative;
  width: 100%;
}

.carousel-wrap img {
  width: 100%;
  height: 100vh;
  object-fit: cover;
}

.slick-prev,
.slick-next {
  position: absolute;
  margin: 0;
}

.slick-next {
  right: 5rem;
}

.slick-prev {
  left: 5rem;
  z-index: 99;
}

.slick-prev::before,
.slick-next::before {
  font-size: 60px;
  color: #009e95;
}

.slick-dots {
  position: absolute;
  bottom: 0;
  padding-bottom: 3rem;
}

.slick-dots li.slick-active button::before {
  color: #009e95;
}

</style>
