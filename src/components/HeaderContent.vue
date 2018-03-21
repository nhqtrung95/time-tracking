<template>
  <div class="header-content">
        <div class="day-view fl-left">
            <h4 class="fl-left">Wednesday <span class="date">21 Mar</span></h4>
            <div class="status fl-left">Pending Approval</div>
        </div>
        <div class="day-view fl-right">
            <div class="day-block fl-left">
            <div class="btn-toggle btn-back radius-left fl-left"></div>
            <div class="btn-toggle today btn-selected fl-left">Today</div>
            <div class="btn-toggle btn-next radius-right fl-left"></div>
            </div>
            <div class="day-block fl-left">
            <div class="btn-toggle calendar fl-left"></div>
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
        font-weight: 600;
    }
    .status {
        display: inline-block;
        font-size: 11px;
        padding: 6px 10px;
        background: #a0a0a0;
        color: white;
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
    .radius-left {
        border-top-left-radius: 3px;
        border-bottom-left-radius: 3px;
    }
    .radius-right {
        border-top-right-radius: 3px;
        border-bottom-right-radius: 3px;
    }
    .btn-back {
        background: url(https://cache.harvestapp.com/assets/3kings/icon-arrow-left-a965e7fe97d11337936210d25a2d50f3352d1635e143b6b00ddbeac6b8c15fe1.svg) center no-repeat, linear-gradient(#fff, #eee);
        opacity: 0.6;
    }
    .btn-next {
        background: url(https://cache.harvestapp.com/assets/3kings/icon-arrow-right-0e6405464566985326afde558c25b16f059e0eefb0ea7354a4e14f2a92c09cfe.svg) center no-repeat, linear-gradient(#fff, #eee);
        opacity: 0.6;
    }
    .calendar {
        width: 40px;
        border-radius: 3px;
        background: url(https://cache.harvestapp.com/assets/3kings/icon-calendar-4723bb6971d6a126250fe3b3857028317083fefc2d3d16798602de0b1b9da413.svg) center no-repeat, linear-gradient(#fff, #eee);;
        opacity: 0.6;
    }
    .btn-switch {
        width: 60px;
        line-height: 33px;
        margin-left: -1px;
    }
</style>

