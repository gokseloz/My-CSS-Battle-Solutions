# 79 - Tambourine

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/79.png)

## My Solution

```
<div class="neck"></div>
<div class="body"></div>
<style>
  body{background:#F3AC3C}
  :before,:after, div{
    content:"";
    position:absolute;
  }
  .body{
    left:45px;
    top:90px;
    width: 120px;
    height: 120px;
    background: #998235;
    border-radius:50%;
    box-shadow:60px 0 0 -10px #998235;
  }
  .body:before{
    left:40px;
    top:40px;
    width:10px;
    height:40px;
    border-radius:10px;
    background:#1A4341;
  }
  .body:after{
    width:40px;
    height:40px;
    background:#1A4341;
    border-radius:50%;
    border:5px solid #F3AC3C;
    left:95px;
    top:35px;
  }
  .neck{
    width:120px;
    heighT:20px;
    background:#1A4341;
    left:205px;
    top:140px;
  }
  .neck:before{
    width:40px;
    height:30px;
    background:#998235;
    border-radius:10px;
    right:-30px;
    top:-5px
  }
  .neck:after{
    width:20px;
    height:4px;
    background:#1A4341;
    righT:-20px;
    top:3px;
    border-radius:5px;
    box-shadow:0px 10px #1A4341
  }
</style>
```
