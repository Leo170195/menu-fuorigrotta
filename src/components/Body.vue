<template>
  <div class="hello">
    
    <!-- <div class="container-fluid m-nav p-0">
        <div class="row">
            <div class="col-12">
                <iframe width="100%" height="860" src="https://www.youtube.com/embed/uZqDSqOEA9Q?controls=0&autoplay=1&showinfo=0&loop=1&modestbranding=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                <h1 class="text-center">Fuorigrotta Beer & Food</h1>
            </div>
        </div>
    </div> -->

    <div class="conatiner mt-5 text-white">
        <div id="beverage" class="row">
            <div class="col-12">
                <h3 class="my-5 text-center">Beverage <i class="fas fa-wine-glass-alt"></i></h3>
            </div>
            <div class="col-12 col-sm-6 col-lg-3 my-2 d-flex justify-content-center">
                <div class="beverage" id="beer" ></div>
            </div>
            <div class="col-12 col-sm-6 col-lg-3 my-2 d-flex justify-content-center">
                <div class="beverage" id="vine" ></div>
            </div>
            <div class="col-12 col-sm-6 col-lg-3 my-2 d-flex justify-content-center">
                <div class="beverage" id="cocktail" ></div>
            </div>
            <div class="col-12 col-sm-6 col-lg-3 my-2 d-flex justify-content-center">
                <div class="beverage" id="rum" ></div>
            </div>
      </div>
    </div>

    <!-- img large -->
    <div class="container-fluid my-5">
        <div class="row">
            <div class="col-12 d-none d-md-block img-large"></div>
        </div>
    </div>

  </div>
</template>

<script>
// import "bootstrap/dist/css/bootstrap.min.css"
// import "bootstrap/dist/js/bootstrap.bundle.min.js"

export default {
  name: 'Body',
//   props: {
//     msg: String
//   }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
