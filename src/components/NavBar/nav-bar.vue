<template>
  <div class="c-nav-bar">
    <div class="headline">
      <slot name="headline" />
    </div>
    <div class="content" v-if="$slots.content">
      <slot name="content" />
    </div>

    {{ msg }}
  </div>
</template>

<script src="./index.js"></script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
