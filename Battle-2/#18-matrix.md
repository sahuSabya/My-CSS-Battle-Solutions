<div class="flex-container">
  <div class="flex-item a"></div>
  <div class="flex-item b"></div>
  <div class="flex-item a"></div>
  <div class="flex-item b"></div>
  <div class="flex-item b"></div>
  <div class="flex-item a"></div>
  <div class="flex-item b"></div>
  <div class="flex-item a"></div>
  <div class="flex-item a"></div>
  <div class="flex-item b"></div>
  <div class="flex-item a"></div>
  <div class="flex-item b"></div>
</div>
<style>
  body{
    background: #5C434C;
    margin: 0;
  }  
  .flex-container{
    display: flex;
    flex-flow: row wrap;
  }
  .flex-item{
    height: 80px;
    width: 80px;
    border-radius: 80px 0 0 0;
    margin: 10px;
  }
  .a{
    background: #F09462;
  }
  .b{
    background: #F5D6B4;
  }
</style>