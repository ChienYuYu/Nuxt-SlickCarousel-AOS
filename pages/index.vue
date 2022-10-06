<template>
  <div class="wrapper">
    <div class="carousel-wrap">
      <SlickCarousel v-bind="slickOptions">
        <div>
          <img
            src="https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1920&q=80"
          >
        </div>
        <div>
          <img
            src="https://images.unsplash.com/photo-1573167507387-6b4b98cb7c13?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1920&q=80"
          >
        </div>
        <div>
          <img
            src="https://images.unsplash.com/photo-1551135049-8a33b5883817?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1920&q=80"
          >
        </div>
      </SlickCarousel>
    </div>

    <section class="container py-5 section1">
      <h2 class="pb-5 text-white text-center" data-aos="fade-down">
        師資陣容
      </h2>
      <div class="row">
        <div class="card col p-0 mx-2" data-aos="fade-up-right">
          <img
            src="https://images.unsplash.com/photo-1543876020-fa0e86833073?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8OHx8a2lsbGVyfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=600&q=60"
            class="card-img-top"
          >
          <div class="card-body">
            <p class="card-text">
              Some quick example text to build on the card title and make up the bulk of the card's
              content.
            </p>
          </div>
        </div>
        <div class="card col p-0 mx-2" data-aos="fade-up">
          <img
            src="https://images.unsplash.com/photo-1564247954985-00cd6f866b7f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MjF8fGtpbGxlcnxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=600&q=60"
            class="card-img-top"
          >
          <div class="card-body">
            <p class="card-text">
              Some quick example text to build on the card title and make up the bulk of the card's
              content.
            </p>
          </div>
        </div>
        <div class="card col p-0 mx-2" data-aos="fade-up-left">
          <img
            src="https://images.unsplash.com/photo-1620853721068-442e16d88afc?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTd8fGtpbGxlcnxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=600&q=60"
            class="card-img-top"
          >
          <div class="card-body">
            <p class="card-text">
              Some quick example text to build on the card title and make up the bulk of the card's
              content.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="container py-5 section2">
      <h2 class="pb-5 text-white text-center" data-aos="fade-down">
        關於我們
      </h2>
      <div class="card mb-3" data-aos="fade-up-right">
        <div class="row no-gutters">
          <div class="col-md-4">
            <img
              src="https://images.unsplash.com/photo-1542744173-8e7e53415bb0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTF8fG1lZXRpbmd8ZW58MHx8MHx8&auto=format&fit=crop&w=600&q=60"
              class="w-100"
            >
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h5 class="card-title">
                Card title
              </h5>
              <p class="card-text">
                This is a wider card with supporting text below as a natural lead-in to additional
                content. This content is a little bit longer.
              </p>
              <p class="card-text">
                <small class="text-muted">Last updated 3 mins ago</small>
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="container py-5 section3">
      <h2 class="pb-5 mb-5 text-white text-center" data-aos="fade-down">
        訂閱方案
      </h2>
      <div class="row justify-content-center">
        <div class="card mx-3" style="width: 18rem;" data-aos="flip-up">
          <div class="card-body">
            <h5 class="card-title">
              Special title treatment
            </h5>
            <p class="card-text">
              With supporting text below as a natural lead-in to additional content.
            </p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card mx-3" style="width: 18rem;" data-aos="flip-up">
          <div class="card-body">
            <h5 class="card-title">
              Special title treatment
            </h5>
            <p class="card-text">
              With supporting text below as a natural lead-in to additional content.
            </p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
        <div class="card mx-3" style="width: 18rem;" data-aos="flip-up">
          <div class="card-body">
            <h5 class="card-title">
              Special title treatment
            </h5>
            <p class="card-text">
              With supporting text below as a natural lead-in to additional content.
            </p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
        </div>
      </div>
    </section>

    <footer class="footer py-4 bg-dark text-center text-light">
      2022 this is footer
    </footer>
  </div>
</template>

<script>

export default {
  name: 'IndexPage',
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
.wrapper {
  background: #333;
}

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
