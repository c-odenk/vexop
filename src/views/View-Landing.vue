<template>
    <div class="view-landing">
        <LayoutHeader />
        <LandingWallpaper />
        <LandingMeetCeo />
        <LandingTargetGroup />
        <LandingService1 />
        <LandingService2 />
        <LandingScalingService />
        <LandingBookingCTA />
        <LayoutFooter />
    </div>
</template>

<script>

import LayoutHeader from '@/components/layout/Layout-Header.vue'
import LandingWallpaper from '@/components/landing/Landing-Wallpaper.vue'
import LandingMeetCeo from '@/components/landing/Landing-Meet-CEO.vue'
import LandingTargetGroup from '@/components/landing/Landing-Target-Group.vue'
import LandingService1 from '@/components/landing/Landing-Service-1.vue'
import LandingService2 from '@/components/landing/Landing-Service-2.vue'
import LandingScalingService from '@/components/landing/Landing-Scaling-Plan.vue'
import LandingBookingCTA from '@/components/landing/Landing-Booking-CTA.vue'
import LayoutFooter from '@/components/layout/Layout-Footer.vue'

export default {
  name: 'View-Landing',
  data: function () {
    return {
    }
  },
  methods: {

  },
  components: {
    LayoutHeader,
    LandingWallpaper,
    LandingMeetCeo,
    LandingTargetGroup,
    LandingService1,
    LandingService2,
    LandingScalingService,
    LandingBookingCTA,
    LayoutFooter
  }
}
</script>

<style lang="scss" scoped>
@import '@/variables/Variables.scss';

.view-landing {
  margin: 0 auto;
}

</style>
