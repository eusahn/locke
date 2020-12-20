<template>
  <div>
    <div class="main-container">
      <Navigation />
      <section class="lg:p-10 p-2">
        <div
          class="grid md:grid-cols-2 justify-between items-center mt-10 sm:mt-5 md:mt-5"
        >
          <div>
            <h1
              class="text-3xl md:text-3xl lg:text-6xl font-bold text-font-one"
            >
              Premium Delivery and Management Tool
            </h1>
            <p class="w-full max-w-xl mt-5 text-font-two tracking-wider">
              For those writers who have writers' block, this can be an
              excellent way to take a step to crumbling those walls.
            </p>
            <div
              class="mt-5 md:text-left text-left sm:text-center lg:text-left"
            >
              <input
                type="text"
                class=" border-primary border rounded-xl px-3 py-3 w-60"
                placeholder="name@company.com"
              />
              <button
                class="block lg:inline-block sm:inline-block sm:ml-2 md:ml-0 md:block lg:ml-4 mt-5 bg-primary text-white px-5 py-3 rounded-xl"
              >
                Try for free
              </button>
            </div>
          </div>

          <div class="hidden sm:hidden md:block lg:block md:p-10 lg:p-0">
            <img src="~@/assets/image_1.png" style="max-height: 800px;" />
          </div>
        </div>
      </section>

      <section class="mt-24 lg:mt-32 pb-10">
        <h2 class="text-center text-4xl font-bold text-font-one mb-20">
          Features that we provide
        </h2>
        <div
          class="grid lg:grid-cols-3 lg:grid-rows-1 gap-10 justify-items-center grid-cols-1 grid-rows-3"
        >
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
      <section class="lg:mt-44">
        <div class="grid lg:grid-cols-2 lg:gap-10 grid-rows-1 grid-cols-1">
          <div class="hidden lg:block">
            <img src="~@/assets/eg.svg" />
          </div>
          <div class="lg:px-10">
            <h4 class="text-4xl text-font-one font-bold lg:pr-10 mt-5">
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
      <section class="lg:mt-44">
        <div class="grid lg:grid-cols-2 lg:gap-10">
          <div class="lg:px-10 mt-5">
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
      <section class="lg:mt-20 lg:p-20 py-5">
        <h2
          class="text-center lg:text-4xl text-xl font-bold text-font-one lg:px-10 mt-10"
        >
          Join Us Today, Be Part Of The Movement
        </h2>
        <div
          class="lg:flex lg:justify-center mt-10 justify-center flex flex-col items-center sm:flex-row lg:items-center text-center"
        >
          <input
            type="email"
            placeholder="your@email.com"
            class="inline-block rounded-xl bg-transparent py-3 px-5 w-60 border border-primary"
          />
          <button
            class="px-8 py-3 mt-5 sm:mt-0 text-white font-bold bg-primary rounded-xl block sm:inline-block sm:ml-2 md:ml-3 lg:ml-2 lg:mt-0"
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

@media screen and (max-width: 1300px) {
  .main-container,
  .footer-container {
    padding: 0 2em;
  }
}
</style>
