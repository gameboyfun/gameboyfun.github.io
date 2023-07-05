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
        <button id="btn" class="ui-btn">
          <span>Resume</span>
        </button>
      </nuxt-link>
      <nuxt-link to="/social">
        <button id="btn" class="ui-btn">
          <span>Social Media</span>
        </button>
      </nuxt-link>
      <nuxt-link to="/experience">
        <button id="btn" class="ui-btn">
          <span>Experience</span>
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
  padding: 10px 20px;
  text-transform: uppercase;
  border-radius: 8px;
  font-size: 17px;
  font-weight: 500;
  color: #ffffff80;
  text-shadow: none;
  background: transparent;
  box-shadow: transparent;
  border: 1px solid #ffffff80;
  transition: 0.5s ease;
  user-select: none;
}

#btn:hover,
:focus {
  color: #ffffff;
  background: gray;
  border: 1px solid gray;
  text-shadow: 0 0 5px #ffffff, 0 0 10px #ffffff;
  box-shadow: 0 0 5px gray, 0 0 20px gray, 0 0 50px gray,
    0 0 100px gray;
}

.ui-btn {
  --btn-default-bg: rgb(41, 41, 41);
  --btn-padding: 15px 20px;
  --btn-hover-bg: rgb(51, 51, 51);
  --btn-transition: 0.3s;
  --btn-letter-spacing: 0.1rem;
  --btn-animation-duration: 1.2s;
  --btn-shadow-color: rgba(0, 0, 0, 0.137);
  --btn-shadow: 0 2px 10px 0 var(--btn-shadow-color);
  --hover-btn-color: #fff;
  --default-btn-color: #fff;
  --font-size: 16px;
  /* 👆 this field should not be empty */
  --font-weight: 600;
  --font-family: Menlo, Roboto Mono, monospace;
  /* 👆 this field should not be empty */
}

/* button settings 👆 */

.ui-btn {
  box-sizing: border-box;
  padding: var(--btn-padding);
  /* display: flex; */
  align-items: center;
  justify-content: center;
  color: var(--default-btn-color);
  font: var(--font-weight) var(--font-size) var(--font-family);
  /* background: var(--btn-default-bg); */
  border: 1px solid #ffffff80;
  cursor: pointer;
  transition: var(--btn-transition);
  overflow: hidden;
  box-shadow: var(--btn-shadow);
}

.ui-btn span {
  letter-spacing: var(--btn-letter-spacing);
  transition: var(--btn-transition);
  box-sizing: border-box;
  position: relative;
  background: inherit;
}

.ui-btn span::before {
  box-sizing: border-box;
  position: absolute;
  content: '';
  background: inherit;
}

.ui-btn:hover,
.ui-btn:focus {
  background: var(--btn-hover-bg);
}

.ui-btn:hover span,
.ui-btn:focus span {
  color: var(--hover-btn-color);
}

.ui-btn:hover span::before,
.ui-btn:focus span::before {
  animation: chitchat linear both var(--btn-animation-duration);
}

@keyframes chitchat {
  0% {
    content: '#';
  }

  5% {
    content: '.';
  }

  10% {
    content: '^{';
  }

  15% {
    content: '-!';
  }

  20% {
    content: '#$_';
  }

  25% {
    content: '№:0';
  }

  30% {
    content: '#{+.';
  }

  35% {
    content: '@}-?';
  }

  40% {
    content: '?{4@%';
  }

  45% {
    content: '=.,^!';
  }

  50% {
    content: '?2@%';
  }

  55% {
    content: '\;1}]';
  }

  60% {
    content: '?{%:%';
    right: 0;
  }

  65% {
    content: '|{f[4';
    right: 0;
  }

  70% {
    content: '{4%0%';
    right: 0;
  }

  75% {
    content: "'1_0<";
    right: 0;
  }

  80% {
    content: '{0%';
    right: 0;
  }

  85% {
    content: "]>'";
    right: 0;
  }

  90% {
    content: '4';
    right: 0;
  }

  95% {
    content: '2';
    right: 0;
  }

  100% {
    content: '';
    right: 0;
  }
}
</style>
