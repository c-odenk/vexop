<template>
  <div class="target-group-section">
    <div class="target-group-section_row">
      <h2> Who <span class="color-blue">is this for? ... </span></h2>
    </div>
    <div class="target-group-section_container-1">
      <img src="@/assets/Target-Group.png">
      <div class="content-box">
        <h3> Do you want more for your business? </h3>
        <p> Our team will go through the execution part of the campaign with yoWatch a 90-second
            explanatory video covering which is VEXOP specifically tailored for, including the ins and outs
            of our services and how we plan to help your business thrive (1 to 1) abd start working towards
            your business goals. </p>
      </div>
    </div>
    <div class="target-group-section_container-2">
      <div class="content-box">
        <h3> Wide Range </h3>
        <p> Offering an array of services for clients: branding, market research, social media management,
            advertising, email marketing and content marketing. </p>
      </div>
      <div class="content-box">
        <h3> Strategic Planning </h3>
        <p> Experienced professionals develop a strategic plan that aligns with the client's overall
            business objectives, whilst accounting for their unique competitive landscape in the industry.</p>
      </div>
      <div class="content-box">
        <h3> Data driven </h3>
        <p> Use data and analytics to inform marketing strategies, track campaign performance, brand
            make adjustments to omptimize approach and achieve better results.</p>
      </div>
      <div class="content-box">
        <h3> Result-Driven </h3>
        <p> Known for delivering measurable results for clients, such as increased website traffic, higher
            conversion rates and improved brand awareness. </p>
      </div>
    </div>
    <div class="button-box">
      <img src="@/assets/Logo.png">
      <p> Vexop | Digital Marketing Agency </p>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Target-Group-Section',
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

.target-group-section {
  padding: 12.5vh 0 20vh 0;
  background-color: $color-background-dark;
  position: relative;

  &_row {
    width: $width-desktop;
    margin: 0 auto 0 auto;

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

  &_container-1 {
    width: $width-desktop;
    margin: 0 auto 0 auto;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    border-radius: 40px;
    background-color: $color-background-white;

    & img {
      width: 50%;
      height: auto;
      border-radius: 40px 0 0 40px;
    }

    & .content-box {
      width: 50%;
      padding: 30px 40px;
      box-sizing: border-box;

      & h3 {
        font-size: $font-size-h3-lg;
        font-weight: $font-weight-h3-lg;
        line-height: $line-height-h2-lg;
        color: $color-text-dark;
        margin: 0 0 2vh 0;
      }

      & p {
        font-size: $font-size-p-lg;
        font-weight: $font-weight-p-lg;
        line-height: $line-height-p-lg;
        letter-spacing: $letter-spacing;
      }
    }
  }

  &_container-2 {
    width: $width-desktop;
    margin: 8vh auto 8vh auto;
    display: flex;
    flex-direction: row;
    justify-content: space-between;

    & .content-box {
      width: 22%;
      text-align: center;

      & h3 {
        font-size: $font-size-h3-lg;
        font-weight: $font-weight-h3-lg;
        line-height: $line-height-h3-lg;
        letter-spacing: $letter-spacing;
        color: $color-text-white;
        margin: 0 0 1vh 0;
      }

      & p {
        font-size: $font-size-p-lg;
        font-weight: $font-weight-p-lg;
        line-height: $line-height-p-lg;
        letter-spacing: $letter-spacing;
        color: $color-text-light;
      }
    }
  }

  & .button-box {
    position: absolute;
    bottom: 3%;
    left: 50%;
    transform: translate(-50%, -50%);

    & img {
      display: block;
      margin: 0 auto;
    }

    & p {
      text-align: center;
      text-transform: uppercase;
      font-size: $font-size-p-lg;
      font-weight: bold;
      letter-spacing: $letter-spacing;
      color: $color-text-white;
      margin: 0 auto;
      padding: 10px 30px;
    }
  }
}

</style>
