<template>
  <div class="">
    <!-- SHOWCASE -->
    <section class="my-20 container md:px-20">
      <div class="showcase py-20 px-16 h-full rounded font-Fraunces">

        <div class="lg:grid lg:grid-cols-2 gap-10">
          <div class="">
            <h1 class="text-white font-extrabold mb-10 text-4xl md:text-7xl  ">Great coffee made simple.</h1>
            <p class="text-white leading-snug text-xl mb-10">Start your mornings with the world’s best coffees. Try our
              expertly curated artisan coffees from ourn
              best roasters delivered directly to your door, at your schedule.</p>


            <button class="bg-green-800 p-3 hover:bg-green-600 text-white rounded">Create Your Plan Now</button>
          </div>

        </div>

      </div>


    </section>

    <!-- FEATURE -->

    <section class="container px-10 md:px-20 pt-10 md:pb-20 bg-white">
      <div class=" max-w-4xl  mx-auto relative">
        <div class="featured  ">
          <h2
          class="mb-1 text-4xl :text-7xl text-center  font-bold leading-loose text-gray-500 lg:absolute -top-14 left-40 tracking-wider">
          Our Collection</h2>
        </div>
        <div class="collection  grid grid-cols-1 mt-16 md:grid-cols-2 lg:grid-cols-4 gap-x-10 lg:gap-x-16 gap-y-10 ">
          <div>
            <img src="~/static/images/gran-espresso.png" alt="">


            <h3 class="mt-4 mb-2 text-base text-center font-bold leading-tight text-gray-900 lg:text-lg">Gran Espresso
            </h3>
            <p class="text-sm text-gray-500 text-center lg:text-base">Light and flavorful blend with cocoa and black
              pepper for an intense experience</p>
          </div>

          <div>
            <img src="~/static/images/planalto.png" alt="">

            <h3 class="mt-4 mb-2 text-base text-center font-bold leading-tight text-gray-900 lg:text-lg">Planalto</h3>
            <p class="text-sm text-gray-500 lg:text-base text-center">Brazilian dark roast with rich and velvety body,
              and hints of fruit and nuts</p>
          </div>

          <div>
            <img src="~/static/images/piccollo.png" alt="">

            <h3 class="mt-4 mb-2 text-base text-center font-bold leading-tight text-gray-900 lg:text-lg">Piccollo</h3>
            <p class="text-sm text-gray-500 text-center  lg:text-base">Mild and smooth blend featuring notes of toasted
              almond dried cherry</p>
          </div>

          <div>
            <img src="~/static/images/danche.png" alt="">

            <h3 class="mt-4 mb-2 text-base text-center font-bold leading-tight text-gray-900 lg:text-lg">Danche</h3>
            <p class="text-sm text-gray-500 text-center  lg:text-base">Ethiopian hard harvested blend densely packed
              with vibrant fruit notes</p>
          </div>



        </div>
      </div>
    </section>

    <!-- WHY CHOOSE US --> 
    <section class=" text-gray-400 bg-gray-900 body-font rounded ">
      <div class="container px-10 md:px-20 mx-auto mt-20">
        <div class="pt-10 pb-10 md:pb-40  relative">
      <div class="flex flex-col text-center w-full md:mb-20">
        <h1 class="sm:text-3xl text-4xl mb-5  font-medium title-font text-white">
          Why Choose Us?
        </h1>

        <p class="md:w-1/2 mx-auto">
          A large part of our role is choosing which particular coffees will be featured in our range.
          This means working closely
          with the best coffee growers to give you a more impactful experience on every level.</p>

      </div>
      <div class="lg:flex  lg:absolute -bottom-40">
        <!-- card 1 -->
        <div class="p-4 lg:w-1/3">
          <div class="
            flex
            rounded-lg
            h-full
            bg-green-800 
            p-10
            flex-col
          ">
            <img class="w-20 mx-auto mb-5" src="~/static/images/coffee-bean.svg" alt="">

            <h2 class="text-white text-center text-xl title-font font-medium mb-5">
              Best Quality
            </h2>

            <div class="flex-grow">
              <p class="leading-relaxed text-base text-center ">
                Discover an endless variety of the world's best artisan coffee from each of our roasters.
              </p>

            </div>
          </div>
        </div>

        <!-- card 2 -->
        <div class="p-4 lg:w-1/3">
          <div class="
            flex
            rounded-lg
            h-full
            bg-green-800 
            p-10
            flex-col
          ">
            <img class="w-20 mx-auto mb-5" src="~/static/images/gift.svg" alt="">

            <h2 class="text-white text-center text-xl title-font font-medium mb-5">
              Exclusive benefits
            </h2>

            <div class="flex-grow">
              <p class="leading-relaxed text-base text-center ">

                Special Offers and swag when you subscribe, including 30% off your first shipment.
              </p>

            </div>
          </div>
        </div>


        <!-- card 3 -->
        <div class="p-4 lg:w-1/3">
          <div class="
            flex
            rounded-lg
            h-full
            bg-green-800 
            p-10
            flex-col
          ">
            <img class="w-20 mx-auto mb-5" src="~/static/images/truck.svg" alt="">

            <h2 class="text-white text-center text-xl title-font font-medium mb-5">
              Free shipping
            </h2>

            <div class="flex-grow">
              <p class="leading-relaxed text-base text-center ">


                We cover the cost and coffee is delivered fast. Peak freshness: guaranteed
              </p>

            </div>
          </div>
        </div>

      </div>
    </div>

      </div>
   

  </section>
   

      <div class="lg:mb-80"></div>


  </div>


</template>

<script>
export default {

}
</script>


<style>
.showcase {
  background: url('./static/images/hero.jpg');
  height: 100%;
  background-position: center;
  background-size: cover;
  font-family: 'Fraunces', serif;

}

.collection{
position:relative;
  z-index:20
}
</style>