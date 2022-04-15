<template>
  <HKOmniComponent />
  <OnyxStudioComponent />
  <GoPlayComponent />
  <AuraComponent />
  <SohoComponent />
</template>

<script>
import HKOmniComponent from "@/components/HKOmniComponent.vue";
import OnyxStudioComponent from "@/components/OnyxStudioComponent.vue";
import GoPlayComponent from "@/components/GoPlayComponent.vue";
import AuraComponent from "@/components/AuraComponent.vue";
import SohoComponent from "@/components/SohoComponent.vue";

export default {
  name: "HomePage",
    components: {
    HKOmniComponent,
    OnyxStudioComponent,
    GoPlayComponent,
    AuraComponent,
    SohoComponent,
  },
  mounted() {
    document.title = "Anggit Yuniar Pradito | Harman Kardon"
  }
}
</script>
