<div class="flex-container">
  <div class="flex-item c g"></div>
  <div class="flex-item s y"></div>
  <div class="flex-item s g"></div>
  <div class="flex-item c y"></div>
  <div class="flex-item t y"></div>
  <div class="flex-item c g"></div>
  <div class="flex-item c y"></div>
  <div class="flex-item t g"></div>
</div>
<style>
  body{
    margin: 0;
    background: #1A4341;
  }
  .flex-item{
    height: 50px;
    width: 50px;
    margin: 10px;
  }
  .flex-container{
    display:flex;
    flex-flow: row wrap;
    margin: 50px auto;
    padding: 30px;
    justify-content: center;
  }
  .g{
    background: #998235;
  }
  .y{
    background: #F3AC3C;
  }
  .c{
    border-radius: 50%;
  }
  .s{
    border-radius: 50% 50% 0 0;
  }
  .t{
    border-radius: 0 0 50% 50%;
  }
</style>