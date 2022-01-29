<template>
  <div class="home">
    <HeaderShayna />
    <CarouselShayna />
    <ItemsShayna />
    <InstaShayna />
    <SponsorShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue'
import CarouselShayna from '@/components/CarouselShayna.vue'
import ItemsShayna from '@/components/ItemsShayna.vue'
import InstaShayna from '@/components/InstaShayna.vue'
import SponsorShayna from '@/components/SponsorShayna.vue'
import FooterShayna from '@/components/FooterShayna.vue'

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    CarouselShayna,
    ItemsShayna,
    InstaShayna,
    SponsorShayna,
    FooterShayna
  }
}
</script>
