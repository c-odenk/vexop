<template>
  <header>
    <nav>
      <div class="header-section_logo">
        <img src="@/assets/Logo.png">
      </div>
      <div class="header-section_navigation">
        <ul>
          <li><router-link to="#"> About </router-link></li>
          <li><router-link to="#"> Services </router-link></li>
          <li><router-link to="#"> Book now </router-link></li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<script>

export default {
  name: 'Header-Section',
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

header {
  background-color: $color-background-dark;

  nav {
    width: $width-desktop;
    margin: 0 auto;
    padding: 2vh 0;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;

    & .header-section_logo {

    }

    & .header-section_navigation {

      & ul {
        display: flex;
        flex-direction: row;
        align-items: center;
        list-style: none;

        & li {
          padding: 5px 25px;

          & a {
            color: $color-text-white;
          }

          &:last-of-type {
            padding: 5px 0px 5px 25px;
          }
        }
      }
    }
  }
}

</style>
