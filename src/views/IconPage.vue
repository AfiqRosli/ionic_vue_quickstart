<template>
  <ion-page>
    <ion-content>
      <ion-icon :icon="heart"></ion-icon>
      <ion-icon icon="infinite-outline"></ion-icon>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { heart } from "ionicons/icons";
import { defineComponent } from "vue";

export default defineComponent({
  name: "IconPage",

  setup() {
    return { heart };
  },
});
</script>
