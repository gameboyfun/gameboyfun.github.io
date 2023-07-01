<template>
  <div
    class="flex justify-center items-center absolute h-screen left-1/2 -translate-x-2/4"
  >
    <div class="text-center">
      <vue-typed-js
        :strings="['First text', 'Second Text']"
        :loop="true"
        :back-delay="3000"
        :back-speed="100"
      >
        <h1 class="text-6xl typing"></h1>
      </vue-typed-js>
      <br />
      <div>1231231</div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      fullName: 'Your Full Name',
    }
  },
}
</script>

<style>
.typed-cursor {
  font-size: 3.75rem;
  line-height: 1;
}
</style>
