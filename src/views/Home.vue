<template>
  <div class="home">
    <Nav />
    <Content />
    <Video />
    <Invitation />
    <Footer/>
  </div>
</template>

<script>
import Footer from "@/components/Footer.vue"
import Invitation from "@/components/Invitation.vue";
import Video from "@/components/Video.vue";
import Nav from "@/components/Nav.vue";
import Content from "@/components/Content.vue";
export default {
  name: "Home",
  components: {
    Nav,
    Footer,
    Content,
    Invitation,
    Video
  }
};
</script>
