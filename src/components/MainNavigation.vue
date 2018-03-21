<template>
  <div class="main-navigation">
      <div class="container clearfix">
          <nav class="fl-left">
              <a href="#"><i class="fas fa-home"></i></a>
              <a href="#">Time</a>
              <a href="#">Project</a>
              <a href="#">Team</a>
              <a href="#">Reports</a>
              <a href="#">Manage</a>
          </nav>
          <nav class="fl-right">
              <a href="#">Help</a>
              <a href="#">Settings</a>
          </nav>
          <div class="clearfix"></div>
      </div> 
  </div>
</template>

<script>
export default {
  name: 'MainNavigation'
}
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/css?family=Raleway');
    .main-navigation {
        background: linear-gradient(#f58933, #f36c00);
    }
    svg {
        color: white;
    }
    .main-navigation a {
        float: left;
        height: 100%;
        padding: 15px 12px;
        color: white;
        font-family: 'Raleway', sans-serif;
        font-size: 15px;
        font-weight: 600;
    }
    .main-navigation a:nth-child(1) {
        background: rgba(255, 255, 255, 0.2);
    }
</style>
