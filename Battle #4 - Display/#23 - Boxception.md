# 23 - Boxception

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/23.png)

## My Solution

```
<div><div><div></div></div></div>
<style>
  body{margin:0;background:#F3AC3C;display:flex;justify-content:center;align-items:center}
  div{
    width:200px;
    height:200px;
    background:#1A4341;
    position:relative;
  }
  div > div{
    width:50%;
    height:50%;
    background:#998235;
    position:absolute;
	bottom:0
  }
  div > div > div{
    background:#F3AC3C;
	right:0
  }
</style>
```
