<template>
  <div
    class="absolute top-1/2 left-1/2 -mr-[50%] -translate-y-1/2 -translate-x-1/2"
  >
    <div class="text-center text-white MartianMono">
      <vue-typed-js
        :strings="[
          'Front-End Developer',
          'Full Time / Part Time',
          'Learning to be Fullstack',
        ]"
        :loop="true"
        :back-delay="3000"
        :back-speed="50"
      >
        <h1 class="text-6xl typing"></h1>
      </vue-typed-js>
      <br />
      <nuxt-link to="/resume">
        <button>
          Resume
          <span></span><span></span><span></span><span></span>
        </button>
      </nuxt-link>
      <nuxt-link to="/social">
        <button>
          Social Media
          <span></span><span></span><span></span><span></span>
        </button>
      </nuxt-link>
      <nuxt-link to="/experience">
        <button>
          Experience
          <span></span><span></span><span></span><span></span>
        </button>
      </nuxt-link>
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
  align-self: flex-end;
  font-size: 3.75rem;
  line-height: 1;
}

button {
  --c: white;
  color: var(--c);
  font-size: 16px;
  border: 0.3em solid var(--c);
  border-radius: 0.5em;
  width: 12em;
  height: 3em;
  text-transform: uppercase;
  font-weight: bold;
  letter-spacing: 0.1em;
  text-align: center;
  line-height: 2em;
  position: relative;
  overflow: hidden;
  z-index: 1;
  transition: 0.5s;
  margin: 1em;
}

button span {
  position: absolute;
  width: 25%;
  height: 100%;
  background-color: var(--c);
  transform: translateY(150%);
  border-radius: 50%;
  left: calc((var(--n) - 1) * 25%);
  transition: 0.5s;
  transition-delay: calc((var(--n) - 1) * 0.1s);
  z-index: -1;
}

button:hover {
  color: black;
}

button:hover span {
  transform: translateY(0) scale(2);
}

button span:nth-child(1) {
  --n: 1;
}

button span:nth-child(2) {
  --n: 2;
}

button span:nth-child(3) {
  --n: 3;
}

button span:nth-child(4) {
  --n: 4;
}
</style>
