<template>
  <div>
    <main-navigation></main-navigation>
    <sub-navigation></sub-navigation>
    <div class="main">
      <div class="container">
        <div class="day-view-table">
          <header-content></header-content>
          <main-content></main-content>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import MainNavigation from '@/components/MainNavigation';
import SubNavigation from '@/components/SubNavigation';
import HeaderContent from '@/components/HeaderContent';
import MainContent from '@/components/MainContent';

export default { 
  components: { MainNavigation, SubNavigation, HeaderContent, MainContent },
  name: 'Main'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

<style>
  * {
    box-sizing: border-box;
    font-family: var(--font-family-sans-serif);
  }
  .fl-left {
    float: left;
  }
  .fl-right {
    float: right;
  }
  a:hover {
    text-decoration: none;
  }
  .main {
    margin-top: 40px;
  }
  .day-view-table {
    margin: 0 228px 0 105px;
  }
  .btn-toggle {
    box-shadow: inset 0 0 0 1px rgba(0,0,0,0.2);
    background: linear-gradient(#fff, #eee);
    cursor: pointer;
  }
  .btn-toggle:hover {
    background: linear-gradient(#f7f7f7, #e6e6e6);
  }
  .btn-selected {
    background: #e4e4e4 !important;
    cursor: default;
  }
</style>
