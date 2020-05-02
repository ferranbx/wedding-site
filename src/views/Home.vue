<template>
  <div id="home" class="page">
    <div id="header">
      <p class="text text-font-accent text-size-larger">{{ $t("logo") }}</p>
      <LocaleChanger />
    </div>
    <div id="content">
      <h1
        class="text text-font-base text-size-largest text-weight-bold text-uppercase"
      >{{ $t("title") }}</h1>
      <h2
        class="text text-font-accent text-size-largest text-color-accent-base"
      >{{ $t("subtitle") }}</h2>
      <p class="text text-font-base text-size-base">{{ $t("letter-1") }}</p>
      <p class="text text-font-base text-size-base">{{ $t("letter-2") }}</p>
      <p class="text text-font-base text-size-base">{{ $t("letter-3") }}</p>
      <p class="text text-font-base text-size-base">{{ $t("letter-4") }}</p>
    </div>
    <div id="action">
      <div class="btn">
        <a href="https://covid19responsefund.org/" target="blank">{{ $t("donate") }}</a>
        <i class="fas fa-arrow-right btn-icon-right"></i>
      </div>
    </div>
    <div id="photo" class="section"></div>
  </div>
</template>

<script>
import LocaleChanger from "@/components/LocaleChanger.vue";

export default {
  name: "Home",
  components: {
    LocaleChanger
  }
};
</script>
