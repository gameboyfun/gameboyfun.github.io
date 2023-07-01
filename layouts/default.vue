<template>
  <div class="full-page-particles">
    <vue-particles
      color="#fff"
      :particle-opacity="0.7"
      :particles-number="80"
      shape-type="star"
      :particle-size="4"
      lines-color="#fff"
      :lines-width="1"
      :line-linked="true"
      :line-opacity="0.4"
      :lines-distance="150"
      :move-speed="3"
      :hover-effect="true"
      hover-mode="grab"
      :click-effect="true"
      click-mode="push"
    />
    <nuxt class="absolute" style="position: absolute" />
  </div>
</template>
