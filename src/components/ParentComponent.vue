<template>
  <div>
    <h1>Parent</h1>
    {{ flex }}
    <Child />
  </div>
</template>

<script>
export default {
  name: "ParentComponent",
  components: {
    Child: () => import("./parent/ChildComponent.vue"),
  },
  data: () => ({
    flex: "flex"
    }),
};
</script>
