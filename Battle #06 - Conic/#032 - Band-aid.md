# 32 - Band-aid

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/32.png)

## My Solution

```
<div></div>
<style>
  body{display:flex;justify-content:center;align-items:center}
  div {
    width:200px;
    heighT:200px;
    position:relative;
    transform:rotate(45deg)
  }
  div:before, div:after{
    content:"";
    position:absolute;
    width:100%;
    height:25%;
    background:#F3AC3C;
    top:50%;
    transform:translateY(-50%);
  }
  div:after{
    width:25%;
    height:100%;
    background:linear-gradient(#A3A368 37.5%, #FBE18C 0 62.5%, #A3A368 0);
    top:0;
    left:50%;
    transform:translateX(-50%);
  }
</style>
```
