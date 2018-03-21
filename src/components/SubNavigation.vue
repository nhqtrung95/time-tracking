<template>
  <div class="sub-navigation">
      <div class="container">
          <div class="fl-left">
              <a href="#">TimeSheet</a>
              <a href="#">Pending Approval</a>
          </div>
          <div class="clearfix"></div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'SubNavigation'
}
</script>
<style scoped>
    .sub-navigation {
        background: #eee;
        box-shadow: inset 0 -1px 0 #ccc;
    }
    .sub-navigation a {
        float: left;
        padding: 12px;
        color: #666;
        font-size: 13px;
        font-weight: 600;
    }
    .sub-navigation a:first-child {
        box-shadow: inset 0 -2px 0 #f36c00;
    }
</style>


