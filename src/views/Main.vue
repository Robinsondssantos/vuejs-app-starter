<template>
  <div class="container">
    <h1>Main</h1>
  </div>
</template>

<script>

export default {
}
</script>

<style scoped>

  .container {
    max-width: 760px;
    background: #fff;
    border-radius: 4px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
    padding: 30px;
    margin: 80px auto;
  }

  @media only screen and (max-width: 600px) {
    .container {
      margin: 80px 20px;
    }
  }

</style>
