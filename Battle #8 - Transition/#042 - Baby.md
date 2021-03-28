# 42 - Baby

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/42.png)

## My Solution

```
<div></div>
<style>
  body{margin:0;background:#293462;display:flex;justify-content:center;align-items:center;}
  div {
    width: 200px;
    height: 200px;
    background-color: #dd6b4d;
    background:radial-gradient(circle at 25% 60%, #FFF1C1 15.5%, transparent 0%), radial-gradient(circle at 75% 60%, #FFF1C1 15.5%, transparent 0%), radial-gradient(circle at 75% 0%, #FFF1C1 20%, transparent 0%), radial-gradient(circle at 25% 0%, #FFF1C1 20%, #FE5F55 0%);
    border-radius:100px 100px 50px 50px;
    position:relative;
  }
  div:before{
    content:"";
    position:absolute;
    width:40px;
    height:10px;
    background:#FFF1C1;
    border-radius:40px;
    bottom:20px;
    left:40%;
  }
</style>
```
