<template>
  <div class="post-part single container">
    <prismic-rich-text class="textslice" :field="slice.primary.text" />
  </div>
</template>

<script>
export default {
  props: ["slice"],
  name: "rich_text"
};
</script>

<style lang="sass">
.textslice
  a
    text-decoration: underline
</style>
