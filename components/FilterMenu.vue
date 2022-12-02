<template>
  <div>
    <div>{{ filtersList }}</div>
    <div>{{ $route }}</div>
  </div>
</template>

// components/FilterMenu.vue
<script>
import { useFiltersStore } from "~/stores/filters";
import { useUserStore } from "@/stores/users";
export default defineComponent({
  setup() {
    const filtersStore = useFiltersStore();
    const filtersList = filtersStore.filtersList;

    return { filtersList };
  },
});
</script>