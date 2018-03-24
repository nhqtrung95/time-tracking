<template>
  <div>
    <main-navigation></main-navigation>
    <sub-navigation></sub-navigation>
    <div class="main">
      <div class="container parent-block">
        <div class="day-view-table">
          <header-content></header-content>
          <main-content></main-content>
        </div>
        <div class="add-new-entry">
          <div class="btn-new-entry"><i class="fas fa-plus"></i></div>
          <div class="text-new-entry">New Entry</div>
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
  .parent-block {
    position: relative;
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
  .add-new-entry {
    position: absolute;
    left: 0;
    top: 56px;
    font-size: 40px;
  }
  .btn-new-entry {
    width: 60px;
    height: 60px;
    line-height: 55px;
    padding: 0;
    background: linear-gradient(#4fb840, #14a000);
    box-shadow: inset 0 0 0 1px rgba(0,0,0,0.2);
    border: 1px solid var(--cyan);
    color: white;
    border-radius: 3px;
    margin-bottom: 10px;
    cursor: pointer;
  }
  .btn-new-entry:hover {
    background: linear-gradient(#4aad3c, #129100);
  }
  .text-new-entry {
    font-size: 12px;
    font-weight: 600;
    color: #888;
  }
</style>
