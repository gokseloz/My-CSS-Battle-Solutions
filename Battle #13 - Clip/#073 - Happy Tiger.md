# 73 - Happy Tiger

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/73.png)

## My Solution

```
<span class="ear"></span>
<span class="ear"></span>
<div class="face">
  <p class="mouth"></p>
  <p class="noseM"></p>
  <a></a>
  <a></a>
</div>
<style>
  body{margin:0;background:#F3AC3C}
  *,:before,:after{
    position:absolute;
  }
  :before,:after{
    content:"";
  }
  div{
    width:150px;
    height:150px;
    background:#998235;
    border-radius:75px 75px 60px 60px;
    lefT:125px;
    top:75px;
    overflow:hidden;
  }
  div:before{
    width:20px;
    height:20px;
    border-radius:50%;
    background:#1A4341;
    left:25px;
    top:60px;
    box-shadow:80px 0 #1A4341;
  }
  div:after{
    border-width:25px;
    border-style:solid;
    border-color:#1A4341 transparent transparent transparent ;
    left:50px;
  }
   .mouth{
    width:100px;
    height:40px;
    backgrounD:#FFFFFF;
    bottom:-1px;
    left:25;
    border-radius:20px 20px 50px 50px
  }
  .noseM{
    width:10px;
    height:30px;
    background:#1A4341;
    left:70px;
    bottom:19px
  }
  div>a{
    width:20px;
    heighT:20px;
    border:10px solid #1A4341;
    border-radius:50%;
    left:40px;
    bottom:25px;
    border-top-color:transparent;
    border-left-color:transparent;
    transform:rotate(45deg);
  }
  div>a:nth-of-type(2){
    left:70px;
  }
  .ear{
    width:40px;
    height:40px;
    background:#1A4341;
    border:10px solid #998235;
    left:115px;
    top:65px;
    border-radius:50%;
  }
  .ear:nth-of-type(2){
    left:225px
  }
</style>
```
