<template>
  <span v-if="option.$isLabel">{{ option.$groupLabel }}</span>
  <span v-else>{{ option ? option.label : '' }}</span>
</template>
<script>
export default {
  props: ['option', 'search', 'index'],
};
</script>
