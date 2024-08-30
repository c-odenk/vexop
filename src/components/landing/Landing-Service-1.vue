<template>
  <div class="service-1-section">
    <div class="service-1-section_row">
      <h2> <span class="color-blue"> Best </span> <br> Selling Service </h2>
      <img src="@/assets/Dashboard-Mockup.png">
    </div>
  </div>
</template>

<script>

export default {
  name: 'Best-Selling-Service-Section',
  data: function () {
    return {
    }
  },
  methods: {
  }
}
</script>

<style lang="scss" scoped>
@import '@/variables/Variables.scss';

.service-1-section {
  padding: 12.5vh 0 5vh 0;

  &_row {
    width: $width-desktop;
    margin: 0 auto;

    & h2 {
      text-transform: uppercase;
      font-size: $font-size-h2-lg;
      font-weight: $font-weight-h2-lg;
      line-height: $line-height-h2-lg;
      letter-spacing: $letter-spacing;
      margin: 0 0 10vh 0;

      & .color-blue {
        color: $color-heading-blue;
      }
    }

    & img {
      display: block;
      width: 55%;
      height: auto;
      margin: 0 auto;
    }
  }
}

</style>
