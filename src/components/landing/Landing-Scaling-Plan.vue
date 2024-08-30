<template>
  <div class="scaling-plan-section">
    <div class="scaling-plan-section_container-1">
      <img src="@/assets/Chart.png">
      <div class="scaling-plan-section_container-1_heading">
        <h2> Our scaling Plan </h2>
        <p> *including our marketing strategy service </p>
      </div>
    </div>
    <div class="scaling-plan-section_container-2">
      <div class="content-box">
        <span class="number"> 1 </span>
        <h3> Contact us </h3>
        <p> Reserve a time slot at a date where it's best for you and we'll have one of our marketing
            consultants reach out to you via zoom call. </p>
      </div>
      <div class="content-box">
        <span class="number"> 1 </span>
        <h3> Pick a Plan </h3>
        <p> Discuss the goals you have for your business and we'll tailor a package of best suited
            for you and your business! </p>
      </div>
      <div class="content-box">
        <span class="number"> 1 </span>
        <h3> Enrolment </h3>
        <p> Our team will go through the execution part of the campaign with you (1 to 1) and start
            working towards your business goals. </p>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Scaling-Plan-Section',
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

.scaling-plan-section {
  padding: 12.5vh 0;

  &_container-1 {
    width: $width-desktop;
    height: 55vh;
    margin: 0 auto 6vh auto;
    border-radius: 40px;
    background-color: white;
    position: relative;

    & img {
      width: 85%;
      height: auto;
      text-align: center;
      position: absolute;
      top: 55%;
      left: 50%;
      transform: translate(-50%, -50%);
    }

    &_heading {
      position: absolute;
      top: 8%;
      left: 5%;

      & h2 {
        margin: 0;
        text-transform: uppercase;
        font-size: $font-size-h2-lg;
        font-weight: $font-weight-h2-lg;
        line-height: $line-height-h2-lg;
        letter-spacing: $letter-spacing;
        color: #034078;
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
    margin: 0 auto;
    display: flex;
    flex-direction: row;
    justify-content: space-between;

    & .content-box {
      width: 30%;
      padding: 40px 30px 70px 30px;
      box-sizing: border-box;
      background: #FFFFFF;
      box-shadow: 0px 4px 45px rgba(0, 0, 0, 0.15);

      & .number {
        display: inline-block;
        font-size: 20px;
        font-weight: bold;
        background-color: #F6F7F9;
        margin: 0 0 2vh 0;
        padding: 15px 20px;
      }

      & h1 {
        margin: 0 0 1vh 0;
        padding: 0;
      }

      & p {
        font-size: $font-size-p-lg;
        font-weight: $font-weight-p-lg;
        line-height: $line-height-p-lg;
        letter-spacing: $letter-spacing;
      }
    }
  }
}

</style>
