<template>
  <div class="h-screen main-bg overflow-y-auto w-full">
    <MainNavbar />

    <section class="hero-section h-[90vh] w-full flex items-center justify-center bg-black/50">
      <div class="grid grid-cols-12 gap-6 max-w-6xl mx-auto">
        <div class="left col-span-7">
          <h2 class="text-5xl text-white font-semibold mb-2">Diet and Health Solutions</h2>
          <h3 class="text-gray-100 text-xl underline">by Dr. XYZ ABCD</h3>
          <ul class="mt-12 space-y-3">
            <li class="flex items-center gap-4">
              <Icon name="material-symbols:checklist" class="h-12 w-12 text-pink-800" />
              <div class="w-full">
                <h3 class="text-semibold text-white text-xl">Doctor-Supervised Plans</h3>
                <p class="text-gray-200 text-sm">Every plan is carefully designed and monitored by Dr. Varun Katyal, ensuring your health and safety are prioritized.</p>
              </div>
            </li>
            <li class="flex items-center gap-4">
              <Icon name="si:dashboard-customize-duotone" class="h-12 w-12 text-pink-800" />
              <div class="w-full">
                <h3 class="text-semibold text-white text-xl">Customized to Your Needs</h3>
                <p class="text-gray-200 text-sm">Our diet plans are tailored to suit your unique health requirements, lifestyle, and preferences.</p>
              </div>
            </li>
            <li class="flex items-center gap-4">
              <Icon name="material-symbols:follow-the-signs" class="h-12 w-12 text-pink-800" />
              <div class="w-full">
                <h3 class="text-semibold text-white text-xl">Easy to Follow</h3>
                <p class="text-gray-200 text-sm">We create simple, practical plans that fit seamlessly into your daily routine, making it easier to achieve your goals.</p>
              </div>
            </li>
            <li class="flex items-center gap-4">
              <button class="w-12 h-12 bg-white rounded-full">
                <Icon name="carbon:result" class="h-8 w-8 text-pink-800" />
              </button>
              <div class="w-full">
                <h3 class="text-semibold text-white text-xl">Fast and Effective Results</h3>
                <p class="text-gray-200 text-sm">Whether it's weight loss or managing PCOD, our plans deliver noticeable improvements, helping you stay motivated and confident in your journey.</p>
              </div>
            </li>
          </ul>
          <button class="rounded-xl bg-pink-700 text-white px-3 py-2 mt-5 border border-pink-800">Get an Instant Quote</button>
        </div>
        <div class="right col-span-5">
          <div class="bg-white p-5 rounded-xl">
            <h2 class="bg-pink-700 text-white p-2 rounded-lg text-center">Free Consultation</h2>
            <div class="mt-6 space-y-4">
              <input type="text" placeholder="Name" class="p-2 w-full border border-gray-300 rounded-lg">
              <input type="email" placeholder="Email" class="p-2 w-full border border-gray-300 rounded-lg">
              <input type="text" placeholder="Mobile" class="p-2 w-full border border-gray-300 rounded-lg">
              <textarea placeholder="Message" class="p-2 w-full h-16 border border-gray-300 rounded-lg"></textarea>
              <button class="border border-pink-300 text-pink-700 bg-pink-100 px-5 py-2.5 w-full rounded-xl">Submit</button>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- About Us -->
    <section class="hero-section w-full bg-white">
      <div class="grid grid-cols-12 max-w-6xl mx-auto gap-12 py-20">
        <div class="col-span-4">
          <img src="https://st3.depositphotos.com/9998432/19099/v/450/depositphotos_190991520-stock-illustration-default-placeholder-doctor-half-length.jpg" alt="" class="shadow-xl rounded-xl border border-gray-100">
        </div>
        <div class="col-span-8 space-y-4 flex flex-col justify-center">
          <h3>ABOUT</h3>
          <h2 class="font-bold text-3xl">DR. XYZ NBCG</h2>
          <p>Dr XYZ is a Celebrity Nutritionist And Wellness Expert. He is the Founder and MD of Diet And Health Solutions.Dr. XYZ clientele includes people from all walks of life including Bollywood stars and beauty queens. He is also an International pageant mentor. Dr. XYZ has been a Mentor as well as a Jury for many prestigious national and international beauty pageants and contests.</p>
          <p><strong>Award:</strong> He has received many prestigious awards, most recent ones being Mahatma Gandhi Excellence Award 2023 and JAI National Award 2024. He anchored a popular TV show called Good Health Show</p>
        </div>
      </div>
    </section>

    <!-- Our Service -->
    <section class="hero-section w-full bg-zinc-50">
      <div class="grid grid-cols-2 max-w-6xl mx-auto gap-12 py-20">
        <div class="space-y-4 flex flex-col justify-center">
          <h3 class="uppercase text-3xl">Our Services</h3>

          <h3 class="uppercase">Perfect</h3>
          <h2 class="font-bold text-3xl uppercase">DR. XYZ NBCG</h2>

          <hr/>

          <p>Achieve your weight loss goals quickly and effortlessly with our customized weight loss plans. Designed to be easy to follow and doctor-supervised, these plans ensure effective and sustainable results. Whether you're just starting your fitness journey or need help breaking through a plateau, our tailored solutions will help you lose weight and feel your best.</p>

          <div class="flex gap-3">
            <button class="rounded-xl bg-green-500 text-white px-4 py-2 border border-green-700">WhatsApp</button>
            <button class="rounded-xl bg-blue-800 text-white px-4 py-2 border border-blue-900">+91 9988776655</button>
          </div>
        </div>
        <div class="">
          <img src="https://media.istockphoto.com/id/1372798207/photo/a-woman-with-belly-with-excess-fat-and-toned-slim-stomach-with-abs-before-and-after-losing.jpg?s=612x612&w=0&k=20&c=ll1S4FDYWlH4IePLO_Ep8jst34V4rm324W0vXnm7MbY=" alt="" class="shadow-xl rounded-xl border border-gray-100">
        </div>
      </div>
    </section>

    <MainFooter />

  </div>
</template>

<script setup>

</script>

<style>
.main-bg{
  background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTvgve0wEUekFR5r0UdyGKOBTPLmLqwui5GFW8o-F7oUzal0F404TnFZB3PXcEpHNOIW74&usqp=CAU');
  background-size: cover;
  background-repeat: no-repeat;
}
</style>