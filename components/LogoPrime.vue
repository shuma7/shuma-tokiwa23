<script lang="ts" setup>

</script>

<template>
  <div class="logo-prime">
    <h1>常盤祭2023</h1>
    <h2>横浜国立大学 常盤祭</h2>
    <hr/>
  </div>
</template>

<style lang="scss" scoped>
.logo-prime {
  display: flex;
  flex-direction: column;
  align-items: center;
  align-self: flex-start;
  margin: .6em;

  > h1 {
    font-size: 2.5em;
    font-weight: 500;
    color: #1d2630;
    margin: .5em .5em .2em;
  }

  > h2 {
    font-size: 1.2em;
    font-weight: 400;
    margin: .5em 1em 1em 1em;
  }

  > hr {
    width: 100%;
    margin: 0;
    border: 1px solid var(--thick-font-color);
  }
}
</style>