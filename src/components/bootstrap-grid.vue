<template>
    <div class="screen screen-grid show-grid">
    <div class="screen-title">Bootstrap 3 Grid System</div>

    <div class="row">
        <div class="col-md-1">.col-md-1</div>
        <div class="col-md-1">.col-md-1</div>
        <div class="col-md-1">.col-md-1</div>
        <div class="col-md-1">.col-md-1</div>
        <div class="col-md-1">.col-md-1</div>
        <div class="col-md-1">.col-md-1</div>
        <div class="col-md-1">.col-md-1</div>
        <div class="col-md-1">.col-md-1</div>
        <div class="col-md-1">.col-md-1</div>
        <div class="col-md-1">.col-md-1</div>
        <div class="col-md-1">.col-md-1</div>
        <div class="col-md-1">.col-md-1</div>
    </div>
    <div class="row">
        <div class="col-md-8">.col-md-8</div>
        <div class="col-md-4">.col-md-4</div>
    </div>
    <div class="row">
        <div class="col-md-4">.col-md-4</div>
        <div class="col-md-4">.col-md-4</div>
        <div class="col-md-4">.col-md-4</div>
    </div>
    <div class="row">
        <div class="col-md-6">.col-md-6</div>
        <div class="col-md-6">.col-md-6</div>
    </div>
    <div class="row">
        <div class="col-md-3">.col-md-3</div>
        <div class="col-md-3">.col-md-3</div>
        <div class="col-md-3">.col-md-3</div>
        <div class="col-md-3">.col-md-3</div>
    </div>
    <div class="row">
        <div class="col-md-9">.col-md-9</div>
        <div class="col-md-3">.col-md-3</div>
    </div>

    <div class="row">
        <div class="col-md-4">.col-md-4</div>
        <div class="col-md-4 col-md-offset-4">.col-md-4 .col-md-offset-4</div>
    </div>
    <div class="row">
        <div class="col-md-3 col-md-offset-3">.col-md-3 .col-md-offset-3</div>
        <div class="col-md-3 col-md-offset-3">.col-md-3 .col-md-offset-3</div>
    </div>
    <div class="row">
        <div class="col-md-6 col-md-offset-3">.col-md-6 .col-md-offset-3</div>
    </div>


    <div class="row">
        <div class="col-sm-9">
        Level 1: .col-sm-9
        <div class="row">
            <div class="col-xs-8 col-sm-6">
            Level 2: .col-xs-8 .col-sm-6
            </div>
            <div class="col-xs-4 col-sm-6">
            Level 2: .col-xs-4 .col-sm-6
            </div>
        </div>
        </div>
    </div>
    </div>
</template>
<style>
  .screen-grid {
    background-color: white;
    color: #333;
  }

  .show-grid [class^=col-] {
      padding-top: 10px;
      padding-bottom: 10px;
      background-color: #eee;
      background-color: rgba(86,61,124,.15);
      border: 1px solid #ddd;
      border: 1px solid rgba(86,61,124,.2);
  }
</style>
