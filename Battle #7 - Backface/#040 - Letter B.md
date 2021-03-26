# 40 - Letter B

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/40.png)

## My Solution

```
<div></div>
<style>
  body{background:#6592CF;display:flex;justify-content:center;align-items:center}
  div {
    width:100px;
    height:100px;
    border:50px solid #243D83;
    border-radius:0 50% 50% 50%;
    position:relative;
  }
  div:before{
    content:"";
    position:absolute;
    background:#6592CF;
    width:50px;
    height:50px;
    top:-50%
  }
</style>
```
