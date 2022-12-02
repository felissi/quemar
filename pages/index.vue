<template>
  <div>
    <div>asd</div>
    <div>qweqwe</div>
    <div>qweqwe</div>
    <FilterMenu />
    <input type="checkbox" v-model="show" />
    <loadAsync v-if="show" />
  </div>
</template>
<script>
export default {
  data() {
    return {
      show: false,
    };
  },
};
</script>