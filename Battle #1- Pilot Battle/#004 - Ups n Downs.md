# 4 - Ups n Downs

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/4.png)

## My Solution

```
<div class="d"></div>
<div class="d d2"></div>
<div class="d"></div>
<style>
  body{
    background-color:#62306D;
    display:flex;
    justify-content:center;
    align-items:center;
  }
  .d{
    width:100px;
    height:200px;
    border-radius:50px;
    background:linear-gradient(#62306D 50%, #F7EC7D 0%);
  }
  .d2{	
    transform:rotateZ(180deg);
  }
</style>
```
