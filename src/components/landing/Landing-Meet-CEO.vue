<template>
  <div class="meet-ceo-section">
    <div class="meet-ceo-section_row">
      <h2> Meet the <span class="color-blue"> CEO ... </span></h2>
    </div>
    <div class="meet-ceo-section_video-container">
      <img src="@/assets/The-CEO.png">
      <p> Wacht a quick 3-minute introductory by Tom, founder/ceo of VEXOP, explaining his mission and vision
          of the company. </p>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Meet-CEO-Section',
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

.meet-ceo-section {
  padding: 7.5vh 0;
  background-color: $color-background-dark;

  &_row {
    width: $width-desktop;
    margin: 0 auto;

    & h2 {
      text-transform: uppercase;
      font-size: $font-size-h2-lg;
      font-weight: $font-weight-h2-lg;
      color: $color-text-white;
      line-height: $line-height-h2-lg;
      letter-spacing: $letter-spacing;
      margin: 0 0 4vh 0;

      & .color-blue {
        color: $color-heading-blue;
      }
    }
  }

  &_video-container {
    width: $width-desktop;
    margin: 0 auto;
    background: rgba(255, 255, 255, 0.06);
    border-radius: 40px 40px 40px 40px;

    & img {
      display: block;
      margin: 0 auto;
      padding: 50px 0 0 0;
      width: 90%;
      height: 55vh;
    }

    & p {
      font-size: $font-size-p-lg;
      font-weight: $font-weight-p-lg;
      line-height: $line-height-p-lg;
      letter-spacing: $letter-spacing;
      color: $color-text-light;
      text-align: center;
      margin: 0;
      padding: 20px 0 25px 0;
    }
  }
}

</style>
