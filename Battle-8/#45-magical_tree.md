<div></div>
<span></span>
<style>
  body{
    background: #1A4341;
    margin: 0;
  }
  div {
    width: 90px;
    height: 180px;
    border: solid #F3AC3C 30px;
    position: absolute;
    background: #1A4341;
    left: 65px;
    top: -30px;
    -webkit-box-reflect: right -28px;
  }
  div:before, div:after{
    content: '';
    position: absolute;
  }
  div:before{
    height: 120px;
    width: 30px;
    border: solid #998235 30px; 
    border-right: none;
    border-top:none;
    right: 0;
  }
  div:after{
    height: 30px;
    width: 150px;
    background: #998235;
    bottom: -90px;
    left: -30px;
  }
  span{
    display: block;
    height: 100px;
    width: 30px;
    background: #F3AC3C;
    position: absolute;
    bottom: 0;
    left: 185px;
  }
</style>