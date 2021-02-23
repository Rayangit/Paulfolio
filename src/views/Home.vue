<template>
  <div class="home">
    <mainHeader />
    <div id="content">
      <contentLine />
      
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import header from "@/containers/header/index.vue";
import contentLine from "@/containers/content-line/index.vue";

@Options({
  components: {
    mainHeader: header,
    contentLine
  }
})
export default class Home extends Vue {}
</script>