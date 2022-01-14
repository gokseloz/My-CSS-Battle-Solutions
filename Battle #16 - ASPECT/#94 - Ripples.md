# 94 - Ripples

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/94.png)

## My Solution

```
<style>
  body{background:radial-gradient(circle at center,
    #F3AC3C 0 20px,
    #0E2E2C 20px 28px,
    #F3AC3C 28px 40px,
    #0E2E2C 40px 50px,
    #998235 50px 60px,
    #0E2E2C 60px 72px,
    #F3AC3C 72px 80px,
    #0E2E2C 80px 94px,
    #F3AC3C 94px 100px
    ,#0E2E2C 0);
}
</style>
```

## Another Solution could be with box-shadow
```
<div></div>
<style>
  body{background:#0E2E2C;display:grid;place-items:center;}
  div{
    width:40px;
    height:40px;
    background:#F3AC3C;
    border-radius:50%;
    box-shadow: 0 0 0 8px #0E2E2C, 0 0 0 20px #F3AC3C, 0 0 0 30px #0E2E2C, 0 0 0 40px #998235, 0 0 0 52px #0E2E2C, 0 0 0 60px #F3AC3C, 0 0 0 74px #0E2E2C, 0 0 0 80px #F3AC3C ;
  }  
</style>
```
