<template>
  <div class="dropdown">
    <v-select v-model="$i18n.locale" :options="langs" :clearable="false"></v-select>
  </div>
</template>

<script>
import Vue from 'vue'
import vSelect from 'vue-select'

Vue.component('v-select', vSelect)

export default {
  name: 'locale-changer',
  data () {
    return { langs: ['ca','de','en','es'] }
  }
}
</script>

<style lang="scss">
@import "vue-select/src/scss/vue-select.scss";
</style>