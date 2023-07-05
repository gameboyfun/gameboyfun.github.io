<template>
  <div
    class="absolute top-1/2 left-1/2 -mr-[50%] -translate-y-1/2 -translate-x-1/2 p-4"
  >
    <div class="flex flex-row flex-wrap gap-4">
      <div class="light-button">
        <a href="https://discordapp.com/users/gameboyfun#0079" target="_blank">
          <button class="bt">
            <div class="light-holder">
              <div class="dot"></div>
              <div id="discordLight" class="light"></div>
            </div>
            <div id="discordHolder" class="button-holder">
              <Tilt :options="options" :parallax="true" class="flex flex-col">
                <svg
                  id="discord"
                  role="img"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M20.317 4.3698a19.7913 19.7913 0 00-4.8851-1.5152.0741.0741 0 00-.0785.0371c-.211.3753-.4447.8648-.6083 1.2495-1.8447-.2762-3.68-.2762-5.4868 0-.1636-.3933-.4058-.8742-.6177-1.2495a.077.077 0 00-.0785-.037 19.7363 19.7363 0 00-4.8852 1.515.0699.0699 0 00-.0321.0277C.5334 9.0458-.319 13.5799.0992 18.0578a.0824.0824 0 00.0312.0561c2.0528 1.5076 4.0413 2.4228 5.9929 3.0294a.0777.0777 0 00.0842-.0276c.4616-.6304.8731-1.2952 1.226-1.9942a.076.076 0 00-.0416-.1057c-.6528-.2476-1.2743-.5495-1.8722-.8923a.077.077 0 01-.0076-.1277c.1258-.0943.2517-.1923.3718-.2914a.0743.0743 0 01.0776-.0105c3.9278 1.7933 8.18 1.7933 12.0614 0a.0739.0739 0 01.0785.0095c.1202.099.246.1981.3728.2924a.077.077 0 01-.0066.1276 12.2986 12.2986 0 01-1.873.8914.0766.0766 0 00-.0407.1067c.3604.698.7719 1.3628 1.225 1.9932a.076.076 0 00.0842.0286c1.961-.6067 3.9495-1.5219 6.0023-3.0294a.077.077 0 00.0313-.0552c.5004-5.177-.8382-9.6739-3.5485-13.6604a.061.061 0 00-.0312-.0286zM8.02 15.3312c-1.1825 0-2.1569-1.0857-2.1569-2.419 0-1.3332.9555-2.4189 2.157-2.4189 1.2108 0 2.1757 1.0952 2.1568 2.419 0 1.3332-.9555 2.4189-2.1569 2.4189zm7.9748 0c-1.1825 0-2.1569-1.0857-2.1569-2.419 0-1.3332.9554-2.4189 2.1569-2.4189 1.2108 0 2.1757 1.0952 2.1568 2.419 0 1.3332-.946 2.4189-2.1568 2.4189Z"
                  ></path>
                </svg>
                <p>Discord</p>
              </Tilt>
            </div>
          </button>
        </a>
      </div>
      <div class="light-button">
        <a
          href="https://www.facebook.com/gameboyfun.blackfamily/"
          target="_blank"
        >
          <button class="bt">
            <div class="light-holder">
              <div class="dot"></div>
              <div id="facebookLight" class="light"></div>
            </div>
            <div id="facebookHolder" class="button-holder">
              <Tilt :options="options" :parallax="true" class="flex flex-col">
                <svg
                  id="facebook"
                  role="img"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                  width="100"
                  height="100"
                >
                  <path
                    d="M11.344,5.71c0-0.73,0.074-1.122,1.199-1.122h1.502V1.871h-2.404c-2.886,0-3.903,1.36-3.903,3.646v1.765h-1.8V10h1.8v8.128h3.601V10h2.403l0.32-2.718h-2.724L11.344,5.71z"
                  ></path>
                </svg>
                <p>Facebook</p>
              </Tilt>
            </div>
          </button>
        </a>
      </div>
      <div class="light-button">
        <a href="https://github.com/gameboyfun" target="_blank">
          <button class="bt">
            <div class="light-holder">
              <div class="dot"></div>
              <div id="githubLight" class="light"></div>
            </div>
            <div id="githubHolder" class="button-holder">
              <Tilt
                :options="options"
                :parallax="true"
                class="flex flex-col items-center justify-center"
              >
                <svg
                  id="github"
                  role="img"
                  viewBox="0 0 17 17"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"
                  ></path>
                </svg>
                <p>Github</p>
              </Tilt>
            </div>
          </button>
        </a>
      </div>
      <div class="light-button">
        <a href="https://www.instagram.com/gamexeres/" target="_blank">
          <button class="bt">
            <div class="light-holder">
              <div class="dot"></div>
              <div id="instagramLight" class="light"></div>
            </div>
            <div id="instagramHolder" class="button-holder">
              <Tilt :options="options" :parallax="true" class="flex flex-col">
                <svg
                  id="instagram"
                  role="img"
                  viewBox="0 0 16 16"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.917 3.917 0 0 0-1.417.923A3.927 3.927 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.916 3.916 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.926 3.926 0 0 0-.923-1.417A3.911 3.911 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0h.003zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599.28.28.453.546.598.92.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.47 2.47 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.478 2.478 0 0 1-.92-.598 2.48 2.48 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233 0-2.136.008-2.388.046-3.231.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92.28-.28.546-.453.92-.598.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045v.002zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92zm-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217zm0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334z"
                  ></path>
                </svg>
                <p>Instagram</p>
              </Tilt>
            </div>
          </button>
        </a>
      </div>
      <div class="light-button">
        <a
          href="https://www.linkedin.com/in/thipakorn-kaewsuwan-b6a9001ba/"
          target="_blank"
        >
          <button class="bt">
            <div class="light-holder">
              <div class="dot"></div>
              <div id="linkedinLight" class="light"></div>
            </div>
            <div id="linkedinHolder" class="button-holder">
              <Tilt :options="options" :parallax="true" class="flex flex-col">
                <svg
                  id="linkedin"
                  role="img"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759 z"
                  ></path>
                </svg>
                <p>Linkedin</p>
              </Tilt>
            </div>
          </button>
        </a>
      </div>
      <div class="light-button">
        <a
          href="https://line.me/ti/p/e5mOUNLzXp"
          target="_blank"
        >
          <button class="bt">
            <div class="light-holder">
              <div class="dot"></div>
              <div id="lineLight" class="light"></div>
            </div>
            <div id="lineHolder" class="button-holder">
              <Tilt :options="options" :parallax="true" class="flex flex-col">
                <svg
                  id="line"
                  role="img"
                  viewBox="0 0 480 480"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M189.425 192C190.406 192 191.203 192.313 191.816 192.939C192.429 193.565 192.736 194.379 192.736 195.38V268.808C192.736 270.936 191.632 272 189.425 272H177.839C175.632 272 174.529 270.936 174.529 268.808V195.38C174.529 194.379 174.866 193.565 175.54 192.939C176.215 192.313 176.981 192 177.839 192H189.425Z M269.057 192C271.142 192 272.184 193.127 272.184 195.38V268.808C272.184 270.936 271.142 272 269.057 272H257.471C256.245 272 255.326 271.562 254.713 270.685L221.793 225.052V268.808C221.793 270.936 220.751 272 218.667 272H207.08C204.874 272 203.77 270.936 203.77 268.808V195.38C203.77 193.127 204.874 192 207.08 192H218.667C219.77 192 220.628 192.438 221.241 193.315L254.161 238.948V195.38C254.161 194.379 254.467 193.565 255.08 192.939C255.693 192.313 256.49 192 257.471 192H269.057Z M161.471 253.596C163.678 253.596 164.782 254.66 164.782 256.789V268.808C164.782 270.936 163.678 272 161.471 272H115.31C113.103 272 112 270.936 112 268.808V195.38C112 193.127 113.103 192 115.31 192H126.897C128.981 192 130.023 193.127 130.023 195.38V253.596H161.471Z M332.69 210.404H301.425V222.986H332.69C334.897 222.986 336 224.05 336 226.178V237.822C336 238.823 335.663 239.668 334.988 240.357C334.314 241.045 333.548 241.39 332.69 241.39H301.425V253.596H332.69C334.897 253.596 336 254.66 336 256.789V268.808C336 270.936 334.897 272 332.69 272H286.529C284.444 272 283.402 270.936 283.402 268.808V195.38C283.402 193.127 284.444 192 286.529 192H332.69C333.548 192 334.314 192.313 334.988 192.939C335.663 193.565 336 194.379 336 195.38V207.211C336 209.34 334.897 210.404 332.69 210.404Z M48 32C21.4903 32 0 53.4903 0 80V432C0 458.51 21.4903 480 48 480H400C426.51 480 448 458.51 448 432V80C448 53.4903 426.51 32 400 32H48ZM371.321 179.528C379.774 196.34 384 213.996 384 232.495C384 262.244 372.571 290.243 349.714 316.492C334.833 334.492 313.077 353.96 284.446 374.896C255.815 395.833 235.667 408.864 224 413.989C216.504 418.767 208.524 414.74 210.071 404.989C210.31 403.364 211.083 398.552 212.393 390.552C212.988 383.177 212.81 378.178 211.857 375.553C210.31 371.553 205.607 368.74 197.75 367.115C172.512 363.616 149.714 355.491 129.357 342.741C109 329.992 93.0179 313.961 81.4107 294.649C69.8036 275.337 64 254.619 64 232.495C64 213.996 68.2262 196.34 76.6786 179.528C85.131 162.716 96.5 148.217 110.786 136.03C125.071 123.843 142.095 114.124 161.857 106.875C181.619 99.6249 202.333 96 224 96C245.667 96 266.381 99.6249 286.143 106.875C305.905 114.124 322.929 123.843 337.214 136.03C351.5 148.217 362.869 162.716 371.321 179.528Z"
                  ></path>
                </svg>
                <p>Line</p>
              </Tilt>
            </div>
          </button>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import Tilt from 'vanilla-tilt-vue'
export default {
  components: {
    Tilt,
  },
  data() {
    return {
      options: {
        ransition: true, // Set a transition on enter/exit.

        axis: null, // What axis should be disabled. Can be X or Y.

        reset: true, // If the tilt effect has to be reset on exit.

        easing: 'cubic-bezier(.03,.98,.52,.99)', // Easing on enter/exit.

        glare: false, // if it should have a "glare" effect

        'max-glare': 0.3, // the maximum "glare" opacity (1 = 100%, 0.5 = 50%)

        'glare-prerender': false, // false = VanillaTilt creates the glare elements for you, otherwise

        // you need to add .js-tilt-glare>.js-tilt-glare-inner by yourself

        'mouse-event-element': null, // css-selector or link to HTML-element what will be listen mouse events
        scale: 3,

        // you need to add .js-tilt-glare>.js-tilt-glare-inner by yourself

        gyroscope: true, // Boolean to enable/disable device orientation detection,

        gyroscopeMinAngleX: -45, // This is the bottom limit of the device angle on X axis, meaning that a device rotated at this angle would tilt the element as if the mouse was on the left border of the element;

        gyroscopeMaxAngleX: 45, // This is the top limit of the device angle on X axis, meaning that a device rotated at this angle would tilt the element as if the mouse was on the right border of the element;

        gyroscopeMinAngleY: -45, // This is the bottom limit of the device angle on Y axis, meaning that a device rotated at this angle would tilt the element as if the mouse was on the top border of the element;

        gyroscopeMaxAngleY: 45, // This is the top limit of the device angle on Y axis, meaning that a device rotated at this angle would tilt the element as if the mouse was on the bottom border of the element;
      },
    }
  },
}
</script>

<style>
.light-button button.bt {
  position: relative;
  height: 200px;
  display: flex;
  align-items: flex-end;
  outline: none;
  background: none;
  border: none;
}

.light-button button.bt .button-holder#discordHolder {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100px;
  width: 100px;
  background-color: #0a0a0a;
  border-radius: 5px;
  color: rgba(88, 101, 242, 1);
  font-weight: 700;
  transition: 300ms;
  outline: #0f0f0f 2px solid;
  outline-offset: 20;
}
.light-button button.bt .button-holder#facebookHolder {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100px;
  width: 100px;
  background-color: #0a0a0a;
  border-radius: 5px;
  color: rgba(59, 89, 152, 1);
  font-weight: 700;
  transition: 300ms;
  outline: #0f0f0f 2px solid;
  outline-offset: 20;
}
.light-button button.bt .button-holder#githubHolder {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100px;
  width: 100px;
  background-color: #0a0a0a;
  border-radius: 5px;
  color: rgba(255, 255, 255, 1);
  font-weight: 700;
  transition: 300ms;
  outline: #0f0f0f 2px solid;
  outline-offset: 20;
}
.light-button button.bt .button-holder#instagramHolder {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100px;
  width: 100px;
  background-color: #0a0a0a;
  border-radius: 5px;
  color: rgba(222, 30, 124, 1);
  font-weight: 700;
  transition: 300ms;
  outline: #0f0f0f 2px solid;
  outline-offset: 20;
}
.light-button button.bt .button-holder#linkedinHolder {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100px;
  width: 100px;
  background-color: #0a0a0a;
  border-radius: 5px;
  color: rgba(0, 119, 181, 1);
  font-weight: 700;
  transition: 300ms;
  outline: #0f0f0f 2px solid;
  outline-offset: 20;
}
.light-button button.bt .button-holder#lineHolder {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100px;
  width: 100px;
  background-color: #0a0a0a;
  border-radius: 5px;
  color: rgba(37, 185, 3, 1);
  font-weight: 700;
  transition: 300ms;
  outline: #0f0f0f 2px solid;
  outline-offset: 20;
}

.light-button button.bt .button-holder svg#discord {
  height: 50px;
  fill: rgba(88, 101, 242, 1);
  transition: 300ms;
}
.light-button button.bt .button-holder svg#facebook {
  height: 50px;
  fill: rgba(59, 89, 152, 1);
  transition: 300ms;
}
.light-button button.bt .button-holder svg#github {
  height: 50px;
  fill: rgba(255, 255, 255, 1);
  transition: 300ms;
}
.light-button button.bt .button-holder svg#instagram {
  height: 50px;
  fill: rgba(222, 30, 124, 1);
  transition: 300ms;
}
.light-button button.bt .button-holder svg#linkedin {
  height: 50px;
  fill: rgba(0, 119, 181, 1);
  transition: 300ms;
}
.light-button button.bt .button-holder svg#line {
  height: 50px;
  fill: rgba(37, 185, 3, 1);
  transition: 300ms;
}

.light-button button.bt .light-holder {
  position: absolute;
  height: 200px;
  width: 100px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.light-button button.bt .light-holder .dot {
  position: absolute;
  top: 0;
  width: 10px;
  height: 10px;
  background-color: #0a0a0a;
  border-radius: 10px;
  z-index: 2;
}

.light-button button.bt .light-holder .light {
  position: absolute;
  top: 0;
  width: 200px;
  height: 200px;
  clip-path: polygon(50% 0%, 25% 100%, 75% 100%);
  background: transparent;
}

.light-button button.bt:hover .button-holder svg#discord {
  fill: rgba(88, 101, 242, 1);
  filter: drop-shadow(2px 2px 4px #000);
}
.light-button button.bt:hover .button-holder svg#facebook {
  fill: rgba(59, 89, 152, 1);
  filter: drop-shadow(2px 2px 4px #000);
}
.light-button button.bt:hover .button-holder svg#github {
  fill: rgba(255, 255, 255, 1);
  filter: drop-shadow(2px 2px 4px #000);
}
.light-button button.bt:hover .button-holder svg#instagram {
  fill: rgba(222, 30, 124, 1);
  filter: drop-shadow(2px 2px 4px #000);
}
.light-button button.bt:hover .button-holder svg#linkedin {
  fill: rgba(0, 119, 181, 1);
  filter: drop-shadow(2px 2px 4px #000);
}
.light-button button.bt:hover .button-holder svg#line {
  fill: rgba(37, 185, 3, 1);
  filter: drop-shadow(2px 2px 4px #000);
}

.light-button button.bt:hover .button-holder#discordHolder {
  color: rgba(88, 101, 242, 1);
  outline: rgba(88, 101, 242, 1) 2px solid;
  outline-offset: 2px;
  text-shadow: 1px 1px 0 #000;
}
.light-button button.bt:hover .button-holder#facebookHolder {
  color: rgba(59, 89, 152, 1);
  outline: rgba(59, 89, 152, 1) 2px solid;
  outline-offset: 2px;
  text-shadow: 1px 1px 0 #000;
}
.light-button button.bt:hover .button-holder#githubHolder {
  color: rgba(255, 255, 255, 1);
  outline: rgba(255, 255, 255, 1) 2px solid;
  outline-offset: 2px;
  text-shadow: 1px 1px 0 #000;
}
.light-button button.bt:hover .button-holder#instagramHolder {
  color: rgba(222, 30, 124, 1);
  outline: rgba(222, 30, 124, 1) 2px solid;
  outline-offset: 2px;
  text-shadow: 1px 1px 0 #000;
}
.light-button button.bt:hover .button-holder#linkedinHolder {
  color: rgba(0, 119, 181, 1);
  outline: rgba(0, 119, 181, 1) 2px solid;
  outline-offset: 2px;
  text-shadow: 1px 1px 0 #000;
}
.light-button button.bt:hover .button-holder#lineHolder {
  color: rgba(37, 185, 3, 1);
  outline: rgba(37, 185, 3, 1) 2px solid;
  outline-offset: 2px;
  text-shadow: 1px 1px 0 #000;
}

.light-button button.bt:hover .light-holder .light#discordLight {
  background: rgb(255, 255, 255);
  background: linear-gradient(
    180deg,
    rgba(88, 101, 242, 1) 0%,
    rgba(255, 255, 255, 0) 75%,
    rgba(255, 255, 255, 0) 100%
  );
}
.light-button button.bt:hover .light-holder .light#facebookLight {
  background: rgb(255, 255, 255);
  background: linear-gradient(
    180deg,
    rgba(59, 89, 152, 1) 0%,
    rgba(255, 255, 255, 0) 75%,
    rgba(255, 255, 255, 0) 100%
  );
}
.light-button button.bt:hover .light-holder .light#githubLight {
  background: rgb(255, 255, 255);
  background: linear-gradient(
    180deg,
    rgba(255, 255, 255, 1) 0%,
    rgba(255, 255, 255, 0) 75%,
    rgba(255, 255, 255, 0) 100%
  );
}
.light-button button.bt:hover .light-holder .light#instagramLight {
  background: rgb(255, 255, 255);
  background: linear-gradient(
    180deg,
    rgba(222, 30, 124, 1) 0%,
    rgba(255, 255, 255, 0) 75%,
    rgba(255, 255, 255, 0) 100%
  );
}
.light-button button.bt:hover .light-holder .light#linkedinLight {
  background: rgb(255, 255, 255);
  background: linear-gradient(
    180deg,
    rgba(0, 119, 181, 1) 0%,
    rgba(255, 255, 255, 0) 75%,
    rgba(255, 255, 255, 0) 100%
  );
}
.light-button button.bt:hover .light-holder .light#lineLight {
  background: rgb(255, 255, 255);
  background: linear-gradient(
    180deg,
    rgba(37, 185, 3, 1) 0%,
    rgba(255, 255, 255, 0) 75%,
    rgba(255, 255, 255, 0) 100%
  );
}
</style>
