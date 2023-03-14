<div>
  <span></span>
  <span></span>
  <span></span>
</div>
<style>
  body{
    margin: 0;
    background: #1A4341;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  div{
    height: 250px;
    width: 250px;
    border-radius: 50%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
        overflow: hidden;
  }
  div:before, div:after{
    display: block;
    content: '';
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
  div:before{
    height: 200px;
    width: 200px;
    background: #998235;
    border-radius: 50%;
  }
  div:after{
    height: 140px;
    width: 200px;
    background: #1A4341;
  }
  span{
    display: block;
    height: 20px;
    width: 300px;
    margin: 10px 0;
    background: #F3AC3C;
    z-index: 5;
  }
</style>