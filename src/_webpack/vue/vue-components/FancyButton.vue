<template>
  <div class="fancy-button">
    <a :href="link" class="button">{{title}}</a>
  </div>
</template>

<script>
export default {
  name: 'FancyButton',
  props: ['title', 'link'],
  data () {
    return {
    }
  }
}
</script>

<style scoped>
  .fancy-button {
    margin: .25em 0;
  }

  .fancy-button .button {
    border: none;
    display: inline-block;
    width: auto;
    height: auto;
    color: #000;
    background: #fff;
    border-radius: 5px;
    font-size: .9em;
    font-weight: 900;
    padding: 1em 2.75em;
  }
</style>
