<template>
  <div class="main">
      {{text + ' Sontaya Rungsaard'}} {{number + 3}}
  </div>
</template>

<script>
export default {
  name: 'Main',
  data () {
    return {
      text: 'Hello',
      number: 0
    }
  }
}
</script>

<style scoped></style>
