<div class="flex-container">
  <div class="flex-item"></div>
  <div class="flex-item b"></div>
  <div class="flex-item"></div>
  <div class="flex-item d"></div>
  <div class="flex-item"></div>
  <div class="flex-item f"></div>
</div>
<style>
  body{
    background-color: #62306D;
  }
  .flex-container {
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    margin-top: 50px;
  }
  .flex-item{
    height: 100px;
    width: 100px;
  }
  .flex-item:nth-child(even){
    background-color: #F7EC7D;
  }
  .b{
    border-radius: 50% 50% 0 0;
  }
  .d, .f{
    border-radius: 0 0 50% 50% ;
  }
</style>
