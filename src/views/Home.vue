<template>
  <div id="home" class="page">
    <div id="main" class="section">
      <div class="section-header">
        <p class="text text-font-accent text-size-large">{{ $t("logo") }}</p>
      </div>
      <div class="section-content">
        <h1 class="text text-font-base text-size-largest">{{ $t("title") }}</h1>
        <h2 class="text text-font-accent text-size-larger text-color-accent-base">{{ $t("subtitle") }}</h2>
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
      <div class="section-footer">
        <LocaleChanger />
      </div>
    </div>
    <div id="side" class="section"></div>
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
