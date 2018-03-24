<template>
  <div class="header-content">
        <div class="day-view fl-left">
            <h4 class="fl-left">Wednesday <span class="date">21 Mar</span></h4>
            <div class="status fl-left">Pending Approval</div>
        </div>
        <div class="day-view fl-right">
            <div class="day-block fl-left">
            <div class="btn-toggle pd-v-7 radius-left fl-left"><i class="fas fa-arrow-left"></i></div>
            <div class="btn-toggle today btn-selected fl-left">Today</div>
            <div class="btn-toggle pd-v-7 radius-right fl-left"><i class="fas fa-arrow-right"></i></div>
            </div>
            <div class="day-block fl-left">
            <div class="btn-toggle calendar pd-v-7 fl-left"><i class="far fa-calendar-alt"></i></div>
            </div>
            <div class="day-block fl-left">
                <div class="btn-toggle btn-switch radius-left btn-selected fl-left">Day</div>
                <div class="btn-toggle btn-switch radius-right fl-left">Week</div>
            </div>
        </div>
        <div class="clearfix"></div>
  </div>
</template>

<script>
export default {
  name: 'HeaderContent'
}
</script>

<style scoped>
    .header-content {
        margin-bottom: 20px;
    }
    .day-view h4 {
        font-weight: 700;
    }
    .status {
        display: inline-block;
        font-size: 11px;
        padding: 3px 10px;
        background: #a0a0a0;
        color: white;
        margin-top: 5px;
        border-radius: 4px;
        font-weight: 600;
        display: inline-block;
    }
    .date {
        margin: 0 7px 0 2px;
        color: #888;
        font-weight: 500;
    }
    .day-block {
        margin: 0 10px;
        font-size: 13px;
        font-weight: bold;
        color: #555;
    }
    .btn-toggle {
        width: 35px;
        height: 35px;
    }
    .today {
        width: auto;
        padding: 10px 13px;
        line-height: 15px;
        margin: 0 -1px;
    }
    .pd-v-7 {
        padding: 7px 0;
    }
    .radius-left {
        border-top-left-radius: 3px;
        border-bottom-left-radius: 3px;
    }
    .radius-right {
        border-top-right-radius: 3px;
        border-bottom-right-radius: 3px;
    }
    .calendar {
        border-radius: 3px;
    }
    .btn-switch {
        width: 60px;
        line-height: 33px;
        margin-left: -1px;
    }
</style>

