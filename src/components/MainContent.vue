<template>
  <div class="main-content">
    <div>
        <ul class="day-in-week">
            <li class="btn-toggle fl-left"><a href="" class="day">M</a><span>0:00</span></li>
            <li class="btn-toggle fl-left"><a href="" class="day">T</a><span>0:00</span></li>
            <li class="btn-toggle fl-left"><a href="" class="day">W</a><span>0:00</span></li>
            <li class="btn-toggle fl-left"><a href="" class="day">Th</a><span>0:00</span></li>
            <li class="btn-toggle fl-left"><a href="" class="day">F</a><span>0:00</span></li>
            <li class="btn-toggle fl-left"><a href="" class="day">S</a><span>0:00</span></li>
            <li class="btn-toggle fl-left"><a href="" class="day">Su</a><span>0:00</span></li>
            <li class="btn-toggle total btn-selected fl-left">Total: <span>0:00</span></li>
            <div class="clearfix"></div>
        </ul>
        <ul class="day-view-entry-list">
            <li class="entry-info">
                <div class="entry-container">
                    <div class="fl-left">
                        <div class="entry-name">[01] Booking Software</div>
                        <div class="entry-content">Business Development</div>
                    </div>
                    <div class="fl-right">
                        <div class="entry-time fl-left">0:00</div>
                        <div class="entry-btn btn-toggle fl-left"><i class="far fa-clock"></i>  Start</div>
                        <div class="edit-entry entry-btn btn-toggle fl-left"><i class="fas fa-pencil-alt"></i></div>
                    </div>
                    <div class="clearfix"></div>
                </div>
            </li>
            <li class="entry-info">
                <div class="entry-container">
                    <div class="fl-left">
                        <div class="entry-name">[01] Booking Software</div>
                        <div class="entry-content">Business Development</div>
                    </div>
                    <div class="fl-right">
                        <div class="entry-time fl-left">0:00</div>
                        <div class="entry-btn btn-toggle fl-left"><i class="far fa-clock"></i>  Start</div>
                        <div class="edit-entry entry-btn btn-toggle fl-left"><i class="fas fa-pencil-alt"></i></div>
                    </div>
                    <div class="clearfix"></div>
                </div>
            </li>
        </ul>
        <div class="day-view-summary">Total: <span>0:00</span></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainContent'
}
</script>

<style src="./css/MainContent.css" scoped></style>
