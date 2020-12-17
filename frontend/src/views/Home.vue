<template>
  <div class="main-container">
    <Navigation />
    <section class="p-10">
      <div class="flex justify-between items-center">
        <div>
          <h1 class="text-6xl font-bold text-font-one">
            Premium Delivery and Management Tool
          </h1>
          <p class="w-full max-w-xl mt-5 text-font-two tracking-wider">
            For those writers who have writers' block, this can be an excellent
            way to take a step to crumbling those walls.
          </p>
          <div class="mt-5">
            <input
              type="text"
              class=" border-primary border rounded-xl px-3 py-3 w-60"
              placeholder="johndoe@youremail.com"
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

    <section class="mt-32">
      <h2 class="text-center text-4xl font-bold text-font-one">
        Services that we provide
      </h2>
    </section>
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
.main-container {
  max-width: 1280px;
  margin: 0 auto;
}
</style>
