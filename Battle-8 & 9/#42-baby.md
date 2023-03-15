<div>
  <span></span>
</div>
<style>
  body{
    background: #293462;
    margin: 0;
  }
  div {
    width: 100px;
    height: 200px;
    border-radius: 100px 0 0 50px;
    background: #FE5F55;
    position: absolute;
    left: 100px;
    top: 50px;
    -webkit-box-reflect: right;
    overflow: hidden;
  }
  div:before,div:after{
    content:'';
    position:absolute;
    background: #FFF1C1;
    border-radius: 50%;
  }
  div:before{
    height: 60px;
    width: 60px;
    right: 20px;
    bottom: 50px;
  }
  div:after{
    height: 100px;
    width: 100px;
    top: -50px;
    right: 0;
  }
  span{
    display: block;
    height: 10px;
    width: 20px;
    border-radius: 10px 0 0 10px;
    background: #FFF1C1;
    position: absolute;
    right: 0;
    bottom: 20px;
  }
</style>