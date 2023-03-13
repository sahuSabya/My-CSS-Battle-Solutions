<div class="s"></div>
<div class="c w"></div>
<div class="c x"></div>
<div class="c y"></div>
<div class="c z"></div>
<style>
  body{
    margin: 0;
    background: #F3AC3C;
  }
  div{
    position: absolute;
  }
  .s{
    width: 200px;
    height: 200px;
    background: #1A4341;
    left: 100px;
    top: 50px;
  }
  .c{
    height: 100px;
    width: 100px;
    background: #F3AC3C;
  }
  .w{
    top: 50px;
    left: 100px;
    border-radius: 0 0 100px;
  }
  .x{
    top: 50px;
    right: 100px;
    border-radius: 0 0 0 100px;
  }
  .y{
    bottom: 50px;
    left: 100px;
    border-radius: 0 100px 0 0;
  }
  .z{
    bottom: 50px;
    right: 100px;
    border-radius: 100px 0 0;
  }
</style>