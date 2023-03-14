<div></div>
<style>
  body{
    background: #6592CF;
    margin: 0;
  }
  div{
    width: 200px;
    height: 200px;
    border-radius: 50%;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background: #243D83;
  }
  div:before{
    content: '';
    display: block;
    width: 100px;
    height: 100px;
    border-radius: 50%;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    background: #6592CF;
  }
  div:after{
    content: '';
    display: block;
    height: 100px;
    width: 100px;
    background: linear-gradient(90deg, #243D83 50%, #6592CF 50%);    
  }
</style>