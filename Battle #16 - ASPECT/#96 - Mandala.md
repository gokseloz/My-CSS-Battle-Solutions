# 96 - Mandala

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/96.png)

## My Solution

```
<div><a></a><a></a><a></a><a></a></div>
<style>
  body{background:#243D83;display:grid;place-items:center}
  a{
    content:"";
    position:absolute;
    width:130px;
    height:130px;
    border-radius:50%;
    background:transparent;
    border:20px solid #243D83;
  }
  div {
    width: 200px;
    height: 200px;
    background: #6592CF;
    border-radius:50%;
    position:relative;
  }
  a{
    top:45%;
    left:50%;
    transform:translateX(-50%);
  }
  a:nth-of-type(2){
    top:-30%;
    left:50%;
    transform:translateX(-50%);
  }
  a:nth-of-type(3){
    top:50%;
    left:45%;
    transform:translateY(-50%);
  }
  a:nth-of-type(4){
    top:50%;
    left:-30%;
    transform:translateY(-50%);
  }
</style>
```
