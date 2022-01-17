# 95 - Pokeball

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/95.png)

## My Solution

```
<div></div>
<style>
  body{background:#6CB3A9;display:grid;place-items:center}
  div{
    width:200px;
    height:200px;
    background:linear-gradient(to top, #FFFFFF 0 45%, #781728 45% 55%, #D25B70 55% 100%);
  	border-radius:50%;
    position:relative;
    display:grid;
    place-items:center;
  }
  div::before{
    content:"";
    position:absolute;
    width:50px;
    height:50px;
    background:#F6DF96;
    border-radius:50%;
    border:10px solid #781728;
  }
  div::after{
     content:"";
    position:absolute;
    width:10px;
    height:20px;
    background:red;
    left:0;
    background:#6CB3A9;
    box-shadow:190px 0 0 0 #6CB3A9
  }
</style>
```
