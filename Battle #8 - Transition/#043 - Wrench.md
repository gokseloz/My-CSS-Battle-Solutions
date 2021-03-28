# 43 - Wrench

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/43.png)

## My Solution

```
<div></div>
<div></div>
<style>
  body{margin:0;background:#6592CF;display:flex;justify-content:center;align-items:center;}
  div {
    margin-top:2px;
    width: 80px;
    height: 182px;
    background:#6592CF;
    border:30px solid #243D83;
    border-radius:80px;
  }
  div:nth-of-type(2){
    margin-left:-30px;
  }
  div:before{
    content:"";
    position:absolute;
    top:30px;
    left:65px;
    width:80px;
    height:242px;
    background:#6592CF;
  }
  div:nth-of-type(2):before{
    left:255px;
  }
</style>
```
