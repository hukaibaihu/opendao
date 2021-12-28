<template>
  <home />
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import Home from '@/components/Home.vue'

@Component({
  name: 'App',
  components: {
    Home,
  },
})
export default class App extends Vue {}
</script>

<style lang="less" src="@/styles/base.less" />
