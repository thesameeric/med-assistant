<template>
  <div class="flex flex-col flex-no-wrap">
    <section class="hero p-5 lg:p-24 h-screen flex items-center">
      <div class="flex flex-col flex-no-wrap w-full lg:w-5/12">
        <h1 class="text-5xl">
          Simple. Secure.<br>Medical Assistant.
        </h1>
        <!-- eslint-disable-next-line max-len -->
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.<br>Repellat suscipit laudantium quod nulla neque cum dolores cupiditate ducimus in eveniet harum minus placeat,</p>
        <div class="flex mt-10 text-xl">
          <a class="flex py-3 px-10 items-center bg-white hover:text-blue-600" href="">
            <i class="text-3xl uil uil-android-alt"></i>
            Download
          </a>
        </div>
      </div>
      <img class="ello ml-20 hidden lg:flex" src="../assets/img/S9.png" alt="">
    </section>
    <section class="flex flex-row flex-no-wrap lg:p-24">
      <ul class="flex flex-col lg:flex-row flex-wrap">
        <li class="flex flex-row w-full lg:w-6/12 flex-no-wrap p-5">
          <img class="icon" src="../assets/img/017-calendar.svg" alt="">
          <div>
            <h4 class="font-bold text-xl">Keep track of your treatment</h4>
            <p><!-- eslint-disable-next-line max-len -->
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia, facilis recusandae, alias quos, corporis sunt doloremque eius voluptas atque et perferendis odio itaque? Odit sit, magni magnam voluptatibus facere sunt!
            </p>
          </div>
        </li>
        <li class="flex flex-row w-full lg:w-6/12 flex-no-wrap p-5">
          <img class="icon" src="../assets/img/009-goal.svg" alt="">
          <div>
            <h4 class="font-bold text-xl">Accurate Diagnostics</h4>
            <!-- eslint-disable-next-line max-len -->
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti nam incidunt quos magni necessitatibus, excepturi culpa repudiandae beatae, reprehenderit consequuntur veritatis soluta praesentium officia alias iure quae eum modi placeat!</p>
          </div>
        </li>
        <li class="flex flex-row w-full lg:w-6/12 flex-no-wrap p-5">
          <img class="icon" src="../assets/img/063-heart.svg" alt="">
          <div>
            <h4 class="font-bold text-xl">Daily health tips</h4>
            <p><!-- eslint-disable-next-line max-len -->
              Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia, facilis recusandae, alias quos, corporis sunt doloremque eius voluptas atque et perferendis odio itaque? Odit sit, magni magnam voluptatibus facere sunt!
            </p>
          </div>
        </li>
        <li class="flex flex-row w-full lg:w-6/12 flex-no-wrap p-5">
          <img class="icon" src="../assets/img/071-email.svg" alt="">
          <div>
            <h4 class="font-bold text-xl">Detailed health record</h4>
            <!-- eslint-disable-next-line max-len -->
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Deleniti nam incidunt quos magni necessitatibus, excepturi culpa repudiandae beatae, reprehenderit consequuntur veritatis soluta praesentium officia alias iure quae eum modi placeat!</p>
          </div>
        </li>
      </ul>
    </section>
    <!-- eslint-disable-next-line max-len -->
    <section class="flex flex-col items-center flex-no-wrap p-5 lg:px-24 py-8 justify-between w-full">
      <h1 class="font-bold mb-30 text-5xl">How it work</h1>
      <div class="flex flex-col items-center lg:flex-row items-center justify-center">
        <div class="flex flex-col lg-full lg:w-5/12 bg-gray-200 p-10">
          <span>
            <!-- eslint-disable -->
            <h3 class="font-semibold text-xl pb-3">Select symptoms or an illness</h3>
            <p class="mb-10">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque nihil animi nam facere eveniet ipsum doloribus a itaque, delectus maxime quidem corporis rem magni? Vero adipisci quae laboriosam asperiores facilis!</p>
          </span>
          <span>
            <!-- eslint-disable -->
            <h3 class="font-semibold text-xl pb-3">Get your diagnostics</h3>
            <p class="mb-10">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque nihil animi nam facere eveniet ipsum doloribus a itaque, delectus maxime quidem corporis rem magni? Vero adipisci quae laboriosam asperiores facilis!</p>
          </span>
          <span>
            <!-- eslint-disable -->
            <h3 class="font-semibold text-xl pb-3">Get Direction to the nearest drug store</h3>
            <p class="mb-10">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque nihil animi nam facere eveniet ipsum doloribus a itaque, delectus maxime quidem corporis rem magni? Vero adipisci quae laboriosam asperiores facilis!</p>
          </span>
        </div>
        <div>
          <img class="ello lg:ml-20 lg:flex" src="../assets/img/mock2.png" alt="">
        </div>
      </div>
    </section>
    <!-- eslint-disable-next-line max-len -->
    <section class="flex flex-col items-center lg:items-start lg:flex-row flex-no-wrap p-5 lg:px-24 py-8 justify-between w-full bg-blue-100">
      <p class="text-3xl mb-8 lg:mb-0 lg:text-5xl">Download on your device</p>
      <a class="flex w-7/12 lg:w-3/12" href="">
        <img class="w-full object-contain" src="../assets/img/play.png" alt="">
      </a>
    </section>
        <!-- eslint-disable-next-line max-len -->
    <section class="flex flex-col lg:flex-row flex-no-wrap lg:px-24 py-3 items-center justify-between w-full">
      <img class="flex w-full object-contain lg:w-7/12" src="../assets/img/talk2.png" alt="">
      <div class="flex flex-col">
        <h4 class="text-3xl">Tell us what you think</h4>
        <p class="text-xl flex items-center">
          <i class="mr-2 text-3xl uil uil-envelope"></i>
          hello@treplabs.co
        </p>
        <div class="flex">
          <a class="flex items-center justify-center font-bold tweetIt" href="">
            <i class="mr-2 text-3xl uil uil-twitter"></i>
            #Itoju
          </a>
        </div>
      </div>
    </section>
    <footer class="flex flex-row flex-no-wrap p-5 lg:px-24 py-8 justify-between w-full">
      <div class="flex flex-col flex-no-wrap font-semibold">
        <p> &copy; copyright. Itoju 2020</p>
        <a class="hover:text-blue-600 hover:underline" href="">Trep Labs Technologies</a>
        <a class="hover:text-blue-600 hover:underline" href="">Delveloper</a>
      </div>
    </footer>
  </div>
</template>
<style lang="scss" scoped>
  .hero {
    background: $secondary-color;
  }
  .ello {
    width: 400px;
    object-fit: contain;
    overflow: hidden;
  }
  .icon {
    width: 50px;
    height: 50px;
    margin: 5px 15px;
    object-fit: contain;
  }
  .tweetIt {
    background: $secondary-color;
    border-radius: 25px;
    padding: 0px 15px;
  }
</style>
<script>
// @ is an alias to /src
export default {
  name: 'Home',
  components: {
  },
};
</script>
