# 99 - Gift Box

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/99.png)

## My Solution

```
<div class="leafCont">
  <p class="leaf left"></p>
  <p class="leaf right"></p>
</div>
<div class="square"></div>
<style>
  body{background:#AC474B}
  ::before,
  ::after{
    content:"";
    position:absolute;
  }
  .square {
    width: 140px;
    height: 140px;
    background: #FFFFFF;
    position:relative;
    display:grid;
    place-items:center;
    left:50%;
    top:30px;
    transform:translateX(-50%)
  }
  .square::before{
    width:100%;
    height:20px;
    background:#AC474B;
  }
  .square::after{
    width:20px;
    height:100%;
    background:#AC474B;
  }
  
  .leafCont{
    display:flex;
    justify-content:center;
    align-items:center;
    position:relative;
    top:26px
  }
  .leaf{
    width:40px;
    height:40px;
    background:#FFFFFF;
    position:relative;
    display:grid;
    place-items:center;
  }
  .left{
    left:5px;
    border-radius:50% 50% 0 50%;
  }
  .right{
    left:-5px;
    border-radius:50% 50% 50% 0;
  }
  .left::before,
  .right::before{
    width:20px;
    height:20px;
    background:#AC474B;
  }
  .left::before{
    border-radius:50% 50% 0 50%;
  }
  .right::before{
    border-radius:50% 50% 50% 0;
  }
</style>
```
