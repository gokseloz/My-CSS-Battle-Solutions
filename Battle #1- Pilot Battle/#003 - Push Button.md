# 3 - Push Button

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/3.png)

## My Solution

```
<div class="rect"></div>
<div class="circle"></div>
<style>
  body{
    background-color:#6592CF;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .rect {
    width: 300px;
    height: 150px;
    background-color:#243D83;
  }
  .circle{
    width:250px;
    height:250px;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%, -50%);
    border-radius:50%;
    background: radial-gradient(#EEB850 14%, #243D83 14% 42.5%, #6592CF 42.5% 100%);
  }
</style>
```
