<script setup lang="ts">

</script>

<template>
  <div class="w-full lg:h-screen h-full m-auto flex items-center justify-cetner py-20 bg-gray-50 dark:bg-gray-900">
    <div class="w-full h-full flex flex-col justify-center items-center sm:px-4 px-2">
      <!--  -->
      <div class="lg:w-[90%] w-full mx-auto flex flex-col lg:gap-6 lg:flex-row items-center justify-center ">
        <div class="relative">
          <!-- Side Img 1 -->
          <img class="absolute z-20 lg:left-[2rem] -top-4 left-[1rem] lg:w-[8rem] lg:h-[8rem] sm:w-[6rem] sm:h-[6rem] w-[3rem] h-[3rem] rounded-full" src="https://urbanstree.com/cdn/shop/files/April23-288_23f0597e-2a8c-4e79-acf0-4f6f5fb8ef10.jpg?v=1688659629" alt="Side Image" />

          <!-- Side Img 2 -->
          <img class="absolute z-20 lg:top-[12rem] sm:top-[11rem] top-[5rem] sm:-left-[3rem] -left-[2rem] lg:w-[8rem] lg:h-[8rem] sm:w-[6rem] sm:h-[6rem] w-[3rem] h-[3rem] rounded-full" src="https://i.etsystatic.com/25460505/r/il/939213/3787088678/il_600x600.3787088678_2ddo.jpg" alt="Side Image 2" />

          <!-- Side Img 3 -->
          <img class="absolute z-20 lg:top-[23rem] sm:top-[20.5rem] top-[10.5rem] left-[2rem] lg:w-[8rem] lg:h-[8rem] sm:w-[6rem] sm:h-[6rem] w-[3rem] h-[3rem] rounded-full" src="https://i5.walmartimages.com/seo/Sexy-Casual-Elegant-Wedding-dress-violet-Summer-Dresses-For-Women-Women-s-Fashion-Solid-Color-V-Neck-Suspender-Sleeveless-Evening-Dress-Purple_9401e9f5-34d7-41a1-86f8-c0e02a3c4ef4.f3d84119b3019af339263eb438c5c8f5.jpegnpm run dev" alt="Side Image 3" />

          <!-- Main Img -->
          <img
              class="rounded-full relative object-cover right-0 lg:w-[30rem] lg:h-[30rem] sm:w-[25rem] sm:h-[25rem] w-[12rem] h-[12rem] outline sm:outline-offset-[.77em] outline-offset-[.37em] outline-green-500"
              src="https://i.ebayimg.com/images/g/40cAAOSw4rhkdGJU/s-l1200.webp" alt="About us" />
        </div>
        <!--  -->
        <div
            class="lg:w-[60%] p-4 w-full h-full shadow-xl shadow-[#852372] flex flex-col justify-center items-center sm:px-6 px-4 rounded-xl">
          <h2 class="text-4xl text-center text-[#852372] font-bold px-4 py-1 md:mt-0 mt-10">
            About Us
          </h2>
          <p class="md:text-3xl text-2xl text-center text-gray-800 dark:text-gray-200 font-bold my-5">We are
            Petal Haven S.C.
          </p>
          <p class="md:text-xl sm:text-lg text-base mt-2 text-justify sm:px-2 dark:text-gray-300">At Petal Haven,
            we believe in the transformative power of flowers. Our blooms are not just arrangements; they are
            expressions of beauty, joy, and emotion. From elegant bouquets to enchanting floral designs, we
            curate every creation with precision and care. Whether it's a celebration, a gesture of love, or a
            moment of solace, Petal Haven's exquisite flowers speak a language of their own, bringing nature's
            beauty to your doorstep. Experience the enchantment of Petal Haven and let flowers tell your story.
          </p>

          <!-- button -->
          <button class="lg:mt-10 mt-6 lg:px-6 px-4 lg:py-4 py-2 bg-[#852372] rounded-sm lg:text-xl text-lg text-white font-semibold">Read More</button>

        </div>

      </div>
    </div>
  </div>
  <section class=" bg-primary text-black py-16 px-6 flex flex-col md:flex-row items-center justify-between gap-8">
    <!-- Left Side: Image -->
    <div class="w-full md:w-5/12 flex justify-center h-full md:justify-end">
      <img src="https://i5.walmartimages.com/seo/HAXMNOU-Women-Short-Sleeve-Evening-Formal-Party-Dress-Wedding-Bridesmaid-Dress-Plus-Size-Solid-Color-Long-Dress-for-Women-Purple-S_f5a8a884-1936-4028-982a-0767f0dd071e.876a6fc3eb5f2c19c73d943eda9412e4.jpeg" alt="About Me" class="w-72 h-96 md:w-80 lg:w-96 object-cover rounded-lg shadow-lg" />
    </div>

    <!-- Right Side: Text Content -->
    <div class="w-full md:w-7/12 text-center md:text-left relative">
      <!-- Vertical Text -->
      <div class="absolute left-[40%] -top-6 md:-left-16  lg:top-0 md:top-6 rotate-0 md:rotate-[-90deg] text-sm tracking-widest">
        <div class="flex items-center justify-center gap-2">
          <div class="w-16 h-[2px] bg-white"></div>
          <p>MORE ABOUT</p>
        </div>
      </div>

      <!-- Main Heading -->
      <h2 class="text-3xl md:text-5xl font-bold leading-tight mb-4 pl-10">
        A Passionate <br> Dresses design
      </h2>

      <!-- Description -->
      <p class="text-black mb-6 text-sm md:text-base leading-relaxed max-w-2xl mx-auto md:mx-0">
        I’m Abdul Baset, a passionate Software Developer with expertise in Vue.js, Laravel, & modern web technologies. I specialize in building user-friendly applications that solve real-world problems. With a deep understanding of frontend development, state management, and API integration, I can bring your ideas to life.
      </p>

      <!-- Buttons -->
      <div class="flex flex-col sm:flex-row gap-4 justify-center md:justify-start">
        <a href="#" class="bg-tertiary text-black font-semibold py-2 px-4 rounded-lg hover:bg-tertiary/80 text-center">
          See Dresses
        </a>
        <a href="#" class="border border-tertiary text-black font-semibold py-2 px-4 rounded-lg hover:bg-tertiary/10 text-center">
          Shop more
        </a>
      </div>
    </div>
  </section>
</template>

<style scoped>

</style>