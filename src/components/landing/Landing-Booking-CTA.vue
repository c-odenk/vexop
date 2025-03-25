<template>
  <div class="booking-cta-section">
    <div class="booking-cta-section_row">
      <div class="booking-cta-section_row_col-1">
        <img src="@/assets/Reviews.png">
      </div>
      <div class="booking-cta-section_row_col-2">
        <h2> Are you <span class="color-blue"> ready to dominate </span> your <span class="color-blue"> industry? </span></h2>
        <p> We tailor our services <span class="color-blue"> directly to our clients </span> needs. </p>
        <p> Book a 15-minute call with our marketing-consultant to help you choose the right service for your business. </p>
        <button> Book Now </button>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Booking-CTA-Section',
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

.booking-cta-section {
  padding: 12.5vh 0;
  background-color: $color-background-dark;

  &_row {
    width: $width-desktop;
    margin: 0 auto;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;

    &_col-1 {
      width: 50%;

      & img {
        display: block;
        margin: 0 auto;
        width: 60%;
        height: 500px;
      }
    }

    &_col-2 {
      width: 45%;

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

      & p {
        font-size: $font-size-p-lg;
        font-weight: $font-weight-p-lg;
        line-height: $line-height-p-lg;
        letter-spacing: $letter-spacing;
        color: $color-text-white;
        text-transform: uppercase;
        margin: 0 0 2vh 0;

        & .color-blue {
          color: $color-heading-blue;
        }

        &:last-of-type {
          margin: 0 0 3vh 0;;
        }
      }

      & button {
        font-size: $font-size-p-lg;
        font-weight: $font-weight-p-lg;
        line-height: $line-height-p-lg;
        letter-spacing: $letter-spacing;
        padding: 10px 20px;
        border-radius: 10px;
        border: .5px solid black;

        &:hover {
          cursor: pointer;
        }
      }
    }
  }
}

</style>
