<template>
  <div class="wallpaper-section">
    <div class="wallpaper-section_row">
      <h1> <span class="color-1"> Do more </span>  <span class="color-2"> with </span> <br> <span class="color-3"> your business </span> </h1>
    </div>
    <div class="button-box">
      <p> Meet Vexop </p>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Wallpaper-Section',
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

.wallpaper-section {
  background-color: $color-background-dark;
  position: relative;

  &_row {
    width: 100%;
    height: 90vh;

    & h1 {
      width: 100%;
      text-transform: uppercase;
      text-align: center;
      position: absolute;
      top: 35%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-style: $font-family;
      font-size: 128px;
      font-weight: 700;
      line-height: 1.1;

      & .color-1 {
        background-image: linear-gradient(90deg, rgba(112, 120, 139, 1), rgba(238, 239, 242, 1));
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
      }

      & .color-2 {
        background-image:linear-gradient(90deg, rgba(233, 239, 255, 0.49), rgba(233, 239, 255, 0.49), rgba(28, 146, 234, 1));
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
      }

      & .color-3 {
        background-image:linear-gradient(90deg, #FFFFFF 49%, #1C92EA 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
      }
    }
  }

  & .button-box {
    position: absolute;
    bottom: 10%;
    left: 50%;
    transform: translate(-50%, -50%);

    & p {
      text-align: center;
      text-transform: uppercase;
      color: $color-text-white;
      border: 4px solid $color-text-white;
      border-radius: 30px;
      margin: 0 auto;
      padding: 10px 30px;
    }
  }
}

</style>
