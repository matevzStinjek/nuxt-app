<template>
  <div>
    test {{ a }}
  </div>
</template>

<script setup>
  const { data: a } = await useFetch('/api/test');
</script>
