<template>
  <nav class="level" id="product-stats-container">
    <div class="level-item has-text-centered">
      <div>
        <p class="heading">Tweets</p>
        <p class="title">3,456</p>
      </div>
    </div>
    <div class="level-item has-text-centered">
      <div>
        <p class="heading">Following</p>
        <p class="title">123</p>
      </div>
    </div>
    <div class="level-item has-text-centered">
      <div>
        <p class="heading">Followers</p>
        <p class="title">456K</p>
      </div>
    </div>
    <div class="level-item has-text-centered">
      <div>
        <p class="heading">Likes</p>
        <p class="title">789</p>
      </div>
    </div>
  </nav>
</template>

<script>

export default {}
</script>

<style lang="scss" scoped>

#product-stats-container {
  margin: 100px 0px;

  @media (max-width: 599px) {
    margin: 60px 0px;
  }
}

</style>