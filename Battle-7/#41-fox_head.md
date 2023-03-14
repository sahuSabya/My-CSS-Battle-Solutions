<div></div>
<style>
  body{
    background: #293462;
  }
  div{
    width: 50px;
    height: 150px;
    background: #FE5F55;
    position: absolute;
    top: 80px;
    right: 50%;
    border-radius: 0 40px 0 0;
    -webkit-box-reflect: right -1px;
  }
  div:before, div:after{
    content: '';
    position: absolute;
  }
  div:before{
    height: 50px;
    width: 50px;
    background: #293462;
    border-radius: 0 40px 0 0;
    bottom: 0;
  }
  div:after{
    height: 30px;
    width: 30px;
    background: #293462;
    border-radius: 50%;
    right: 5px;
    bottom: 60px;
  }
</style>