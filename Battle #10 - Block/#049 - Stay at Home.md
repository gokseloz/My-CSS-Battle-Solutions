# 49 - Stay at Home

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/49.png)

## My Solution

```
<span></span>
<div></div>
<style>
  body{margin:0;background-color:#1A4341;background:#6592CF;display:flex;flex-direction:column;justify-content:center;align-items:center;}
  span{
    border-width:100px;
    border-style:solid;
    border-color:transparent transparent #243D83 transparent;
    margin-top:-50px;
  }
  div {
   	width:150px;
    height:100px;
    border-radius:0 0 10px 10px;
   	background:#243D83;
    position:relative;
  }
  div:after,div:before{
    content:"";
    position:absolute;
    width:50px;
    height:50px;
    background:#EEB850;
    border-radius:10px 10px 0 0;
    left:33%;
    bottom:0;
  }
  div:before{
    width:100px;
    height:10px;
    border-radius:10px;
    left:16.5%;
    top:-5;
  }
</style>
```
