<template>
  <div>
    <div class="main-container">
      <Navigation />
      <section class="p-10">
        <div class="flex justify-between items-center">
          <div>
            <h1 class="text-6xl font-bold text-font-one">
              Premium Delivery and Management Tool
            </h1>
            <p class="w-full max-w-xl mt-5 text-font-two tracking-wider">
              For those writers who have writers' block, this can be an
              excellent way to take a step to crumbling those walls.
            </p>
            <div class="mt-5">
              <input
                type="text"
                class=" border-primary border rounded-xl px-3 py-3 w-60"
                placeholder="name@company.com"
              />
              <button class="ml-4 bg-primary text-white px-5 py-3 rounded-xl">
                Try for free
              </button>
            </div>
          </div>

          <div>
            <img src="~@/assets/image_1.png" style="max-height: 800px;" />
          </div>
        </div>
      </section>

      <section class="mt-32 pb-10">
        <h2 class="text-center text-4xl font-bold text-font-one mb-20">
          Features that we provide
        </h2>
        <div class="grid grid-cols-3 justify-items-center">
          <div
            class="bg-black w-72 h-96 rounded-xl px-5 text-center"
            style="background-color: #7681B3"
          >
            <img
              src="~@/assets/day78-wallet.svg"
              class="inline-block mt-5 h-40"
            />
            <h3 class="text-2xl text-white font-bold text-center px-5">
              Be efficient, and multitask
            </h3>
            <p
              class="text-white text-center mt-5 tracking-wider text-base px-3"
            >
              Get more done, in shorter amount of time. Avoid losing track of
              what you were doing.
            </p>
          </div>
          <div
            class="bg-black w-72 h-96 rounded-xl px-5 text-center"
            style="background-color: #D9F0FF"
          >
            <img
              src="~@/assets/day77-pocket-knief.svg"
              class="inline-block mt-5 h-40"
            />
            <h3 class="text-2xl text-font-one font-bold text-center px-5">
              Be organized, and fast
            </h3>
            <p
              class="text-font-one text-center mt-5 tracking-wider text-base px-3"
            >
              Have all your needs in one place.
            </p>
          </div>
          <div
            class="bg-black w-72 h-96 rounded-xl px-5 text-center"
            style="background-color: #A3D5FF"
          >
            <img src="~@/assets/day80-tea.svg" class="inline-block mt-5 h-40" />
            <h3 class="text-2xl text-font-one font-bold text-center px-5">
              Learn the discipline, and have a smile
            </h3>
            <p
              class="text-font-one text-center mt-5 tracking-wider text-base px-3"
            >
              Make a coffee while you're at it.
            </p>
          </div>
        </div>
      </section>
      <section class="mt-44">
        <div class="grid grid-cols-2 gap-10">
          <div>
            <img src="~@/assets/eg.svg" />
          </div>
          <div class="px-10">
            <h4 class="text-4xl text-font-one font-bold pr-10 mt-5">
              Why you need our management product
            </h4>
            <p class=" text-font-two mt-10">
              Random sentences can also spur creativity in other types of
              projects being done. If you are trying to come up with a new
              concept, a new idea or a new product, a random sentence may help
              you find unique qualities you may not have considered.
            </p>

            <button
              class="px-8 py-3 text-white font-bold bg-primary rounded-xl mt-10"
            >
              Learn More
            </button>
          </div>
        </div>
      </section>
      <section class="mt-44">
        <div class="grid grid-cols-2 gap-10">
          <div class="px-10">
            <h4 class="text-4xl text-font-one font-bold pr-10 mt-5">
              Be different, from everybody
            </h4>
            <p class=" text-font-two mt-10 mb-10">
              Random sentences can also spur creativity in other types of
              projects being done. If you are trying to come up with a new
              concept, a new idea or a new product, a random sentence may help
              you find unique qualities you may not have considered.
            </p>

            <img src="~@/assets/apple.svg" class="inline-block" />
            <img src="~@/assets/google.svg" class="inline-block" />
          </div>
          <div>
            <img src="~@/assets/eg2.svg" />
          </div>
        </div>
      </section>
      <section class="mt-20 p-20">
        <h2 class="text-center text-4xl font-bold text-font-one px-10">
          Join Us Today, Be Part Of The Movement
        </h2>
        <div class="flex justify-center mt-10 items-center">
          <input
            type="email"
            placeholder="your@email.com"
            class="inline-block rounded-xl bg-transparent py-3 px-5 w-60 border border-primary"
          />
          <button
            class="px-8 py-3 text-white font-bold bg-primary rounded-xl ml-5"
          >
            Join Us
          </button>
        </div>
      </section>
    </div>
    <footer class="bg-primary py-10">
      <div class="footer-container p-10">
        <div class="grid grid-cols-2">
          <ul>
            <li>
              <h5 class="text-white font-bold text-2xl">Locke</h5>
              <p class="text-white tracking-widest">Be smart. Be with us.</p>
            </li>
            <li class="mt-10">
              <a class="text-white" href="#">Home</a>
            </li>
            <li>
              <a class="text-white" href="#">Contact Us</a>
            </li>
            <li>
              <a class="text-white" href="#">About</a>
            </li>
          </ul>
          <div>
            <p class="text-white opacity-70">
              Your Name <br />P.O. Box 283 8562 Fusce Rd. <br />Frederick
              Nebraska 20620 <br />(123) 456 7890
            </p>
            <p></p>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
import { Vue, Component } from "vue-property-decorator";
import Navigation from "@/components/Navigation.vue";
@Component({
  components: {
    Navigation
  }
})
export default class Home extends Vue {
  title = "Hello World";
}
</script>
<style lang="scss" scoped>
.main-container,
.footer-container {
  max-width: 1280px;
  margin: 0 auto;
}
</style>
