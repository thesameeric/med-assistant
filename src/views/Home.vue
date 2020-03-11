<template>
  <div class="flex flex-col flex-no-wrap">
    <section class="hero p-5 lg:p-24 h-screen flex items-center">
      <div class="flex flex-col flex-no-wrap w-full lg:w-5/12">
        <h1 class="text-5xl">
          Simple. Secure.<br>Medical Assistant.
        </h1>
        <!-- eslint-disable-next-line max-len -->
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.<br>Repellat suscipit laudantium quod nulla neque cum dolores cupiditate ducimus in eveniet harum minus placeat,</p>
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
    <!-- eslint-disable-next-line max-len -->
    <section class="flex flex-col lg:flex-row flex-no-wrap p-5 lg:px-24 py-8 justify-between w-full bg-blue-100">
      <p class="text-3xl lg:text-5xl">Download on your device</p>
      <a class="flex w-9/12 lg:w-3/12" href="">
        <img class="object-contain" src="../assets/img/play.png" alt="">
      </a>
    </section>
    <footer class="flex flex-row flex-no-wrap px-24 py-8 justify-between w-full">
      <div class="font-semibold">
        <p> &copy; copyright. Itoju 2020</p>
        <a href="">Trep Labs Technologies</a>
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
