# 92 - Squeeze

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/92.png)

## My Solution

```
<div></div>
<style>
  body{background:#6592CF;display:grid;place-items:center;}
  ::before,::after{
    content:"";
    position:absolute;
  }
  div{
    width:200px;
    height:200px;
    background:#243D83;
    border-radius:50%;
    color:#243D83;
    box-shadow:226px 0, -226px 0;
  }
  div::before{
    background:#243D83;
    width:100%;
    height:50px;
    top:50%;
    transform:translateY(-50%);
    left:0;
  }
  div::after{
    width:32px;
    height:30px;
    border-radius:50%;
    background:#6592CF;
    left:71px;
    top:110;
    color:#6592CF;
    box-shadow:0 50px, 226px 0, 226px 50px
  }
</style>
```
