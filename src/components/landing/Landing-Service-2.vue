<template>
  <div class="service-2-section">
    <div class="service-2-section_row">
        <h2> <span class="color-blue"> Top </span> Selling Service </h2>
    </div>
    <div class="service-2-section_img-container">
      <div class="img-container-1"><img src="@/assets/Service-1.png"></div>
      <div class="img-container-2"><img src="@/assets/Service-2.png"></div>
      <div class="img-container-3"><img src="@/assets/Service-3.png"></div>
      <div class="img-container-4"><img src="@/assets/Service-4.png"></div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Top-Selling-Service-Section',
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

.service-2-section {
  padding: 5vh 0 7.5vh 0;

  &_row {
    width: $width-desktop;
    margin: 0 auto 0 auto;

    & h2 {
      text-transform: uppercase;
      font-size: $font-size-h2-lg;
      font-weight: $font-weight-h2-lg;
      line-height: $line-height-h2-lg;
      letter-spacing: $letter-spacing;
      margin: 0 0 4vh 0;

      & .color-blue {
        color: $color-heading-blue;
      }
    }
  }

  &_img-container {
    width: $width-desktop;
    margin: 0 auto 0 auto;
    display: grid;
    grid-template-columns: 70% 20%;
    grid-template-rows: 33% 33% 33%;
    grid-column-gap: 8%;
    grid-row-gap: 2.5%;

    & .img-container-1 {
      grid-column-start: 1;
      grid-column-end: 2;
      grid-row-start: 1;
      grid-row-end: 4;

      & img {
        width: 100%;
        height: auto;
      }
    }

    & .img-container-2 {
      grid-column-start: 2;
      grid-column-end: 3;
      grid-row-start: 1;
      grid-row-end: 2;

      & img {
        width: 100%;
        height: auto;
      }
    }

    & .img-container-3 {
      grid-column-start: 2;
      grid-column-end: 3;
      grid-row-start: 2;
      grid-row-end: 3;

      & img {
        width: 100%;
        height: auto;
      }
    }

    & .img-container-4 {
      grid-column-start: 2;
      grid-column-end: 3;
      grid-row-start: 3;
      grid-row-end: 4;

      & img {
        width: 100%;
        height: auto;
      }
    }
  }
}

</style>
