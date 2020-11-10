<template>
  <div>
    <HeaderMenu />
    <MainBanner />
    <MainSpotlight />
    <MainArticle />
    <FooterForm />
    <FooterContact />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderMenu from "../components/header-menu";
import MainBanner from "../components/main-banner";
import MainSpotlight from "../components/main-spotlight";
import MainArticle from "../components/main-article";
import FooterForm from "../components/footer-form";
import FooterContact from "../components/footer-contact";

export default {
  name: 'Home',
  components: {
    HeaderMenu,
    MainBanner,
    MainSpotlight,
    MainArticle,
    FooterForm,
    FooterContact
  },
};
</script>
