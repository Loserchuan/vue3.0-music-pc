<!-- 发现音乐 -->
<template>
  <div class="discovery-wrapper">
    <Banner />
    <RecommendList />
    <NewSongs />
    <RecommendMV />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Banner from "./banner.vue";
import RecommendList from "./recommendList.vue";
import NewSongs from "./newSongs.vue";
import RecommendMV from "./recommendMV.vue";

export default defineComponent({
  name: "discorvery",
  components: {
    Banner,
    RecommendList,
    NewSongs,
    RecommendMV
  }
});
</script>

<style lang="scss" scoped>
.discovery-wrapper {
  padding: 18px 32px;
}
</style>
