<template>
  <BlurCard>
    <h1 class="prose text-4xl text-white flex items-center gap-4">
      <RenderAvatar>
        <img :src="companyImg" />
      </RenderAvatar>
      {{ company }}
    </h1>
    <ul v-if="start && end">
      <li>{{ start }} - {{ end }}</li>
    </ul>
    <h1 class="prose text-4xl text-white my-4">Responsibility</h1>
    <div
      v-for="(data, index) in responsibility"
      :key="`responsibility-${index}`"
      class="flex mb-2"
    >
      📌 {{ data }}
    </div>
    <h1 class="prose text-4xl text-white my-4">Projects</h1>
    <div class="flex flex-wrap">
      <div
        v-for="(project, index) in left"
        :key="`project-left-${index}`"
        class="flex mb-2 w-full md:w-1/2"
      >
        📌 {{ project }}
      </div>
      <div
        v-for="(project, index) in right"
        :key="`project-right-${index}`"
        class="flex mb-2 w-full md:w-1/2"
      >
        📌 {{ project }}
      </div>
    </div>
    <h1 class="prose text-4xl text-white my-4">Tools</h1>
    <div class="flex flex-wrap gap-4">
      <RenderIcon
        v-for="(tool, index) in tools"
        :key="`tools-${index}`"
        :icon-name="tool"
      />
    </div>
  </BlurCard>
</template>

<script>
import BlurCard from './blurCard.vue'
import RenderIcon from './icon/renderIcon.vue'
import RenderAvatar from './renderAvatar.vue'
export default {
  components: { BlurCard, RenderIcon, RenderAvatar },
  props: {
    companyImg: {
      type: String,
      required: true,
    },
    company: {
      type: String,
      required: true,
    },
    start: {
      type: String,
      required: true,
    },
    end: {
      type: String,
      required: true,
    },
    responsibility: {
      type: Array,
      required: true,
    },
    projects: {
      type: Array,
      required: true,
    },
    tools: {
      type: Array,
      required: true,
      default: function () {
        return []
      },
    },
  },
  data() {
    return {
      left: null,
      right: null,
    }
  },
  mounted() {
    const middle = Math.ceil(this.projects.length / 2)
    this.left = this.projects.slice(0, middle)
    this.right = this.projects.slice(middle)
  },
}
</script>
