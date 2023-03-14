<div class="flex-container">
  <div class="flex-item"></div>
  <div class="flex-item"></div>
  <div class="flex-item"></div>
  <div class="flex-item"></div>
  <div class="flex-item"></div>
</div>
<style>
  body{
    background: #1A4341;
    margin: 0;
  }
  .flex-container{
    display: flex;
    flex-flow: row nowrap;
    justify-content: space-evenly;
  }
  .flex-item{
    width: 50px;
    height: 200px;
  }
  .flex-item:nth-child(odd){
    background: #F3AC3C;
    margin: 100px 0 0 0;
    border-radius: 50px 50px 0 0;
  }
  .flex-item:nth-child(even){
    background: #998235;
    border-radius: 0 0 50px 50px;
  }
</style>