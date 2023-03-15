<div>
  <span></span>
  <span></span>
  <span></span>
  <span></span>
  <span></span>   
</div>
<style>
  body{
    background: #1A4341;
  }
  div{
    width: 160px;
    height: 180px;
    background: #1A4341;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    overflow: hidden;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
  }
  div:before{
    content: '';
    position: absolute;
    height: 300px;
    width: 300px;
    background: #1A4341;
    border-radius: 50%;
    left: -270px;
    top: -60px;
    -webkit-box-reflect: right 100px;
  }
  span{
    height: 20px;
    width: 160px;
    background: #F3AC3C;
    display: block;
  }
</style>