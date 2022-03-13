# 98 - Candle

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/98.png)

## My Solution

```
<div class="candle">
  <p class="candle-bottom"></p>
</div>
<div class="flame"></div>
<style>
  body{background:#14313E;display:grid;place-items:center}
  .candle {
    width: 80px;
    height: 100px;
    background: #BA3E46;
    position:absolute;
    top:42%
  }
  .candle-bottom{
    position:absolute;
    width:100%;
    height:30px;
    background:#BA3E46;
    bottom:-30px;
    border-radius:50%
  }
  .candle::before,
  .candle::after{
    content:"";
    position:absolute;
    left:50%;
    transform:translateX(-50%);
    height:30px;
    border-radius:50%
  }
  .candle::before{
    width:100%;
    background:#F3695A;
    top:-16px;
  }
  .candle::after{
    width:76%;
    background:#14313E;
    top:-26px;
  }
  .flame{
    width:30px;
    height:50px;
    background:#F3AC3C;
    border-radius:35px 0 35px 0;
    order:-1;
    position:absolute;
    top:60px;
    left:200px;
  }
</style>
```
