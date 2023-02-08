<!-- Please remove this file from your project -->
<template>
  <div>
    <div class="banner">
      <div class="container">
        <div class="row">
          <div class="banner-event-name text-center">
            Sự kiện MISA
          </div>
        </div>
      </div>
    </div>
    <FilterHome />
  </div>
</template>

<script>
import FilterHome from '../pages/FilterHome/FilterHome.vue';
export default {
  name: 'NuxtTutorial',
  components: {
    FilterHome
  }
}
</script>

<style>
.banner {
  background: url("../static/img/home/bg_banner.jpg");
  background-size: cover;
  color: #fff;
  padding: 50px 0;
  overflow: hidden;
}

.banner-event-name{
  font-size: 30px;
}
</style>

<!-- set NODE_OPTIONS=--openssl-legacy-provider -->