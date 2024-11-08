<template>
  <div
    class="absolute top-1/2 left-1/2 -mr-[50%] -translate-y-1/2 -translate-x-1/2 p-4"
  >
    <div class="text-center text-white MartianMono flex flex-col gap-4">
      <vue-typed-js
        :strings="stringList"
        :loop="true"
        :back-delay="3000"
        :back-speed="50"
      >
        <h1 class="text-6xl typing"></h1>
      </vue-typed-js>
      <div class="flex justify-center gap-4 flex-wrap">
        <nuxt-link
          v-for="{ linkTo, title } in buttonList"
          :key="linkTo"
          :to="linkTo"
        >
          <button id="btn" class="ui-btn">
            <span>{{ title }}</span>
          </button>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
import 'assets/css/ui-button.css'

export default {
  data() {
    return {
      stringList: [
        'Front-End Developer',
        'Full Time / Contract',
        'Learning to be Fullstack',
      ],
      buttonList: [
        {
          linkTo: '/resume',
          title: 'Resume',
        },
        {
          linkTo: '/social',
          title: 'Social Media',
        },
        {
          linkTo: '/experience',
          title: 'Experience',
        },
      ],
    }
  },
}
</script>
