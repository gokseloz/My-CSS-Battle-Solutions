# 15 - Overlap

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/15.png)

## My Solution

```
<div></div>
<div></div>
<style>
  body{margin:0;background:#09042A;display:flex;justify-content:center;align-items:center}
 div {
    width: 150px;
    height: 150px;
    border-radius:50%;
    background-color: #E78481;
  }
  div:nth-of-type(1){
     width: 150px;
    height: 150px;
    border-radius:50%;
    background-color: #7B3F61;
    margin-right:-50px;
    background:radial-gradient(circle at 118% 50%, #09042A 40%, #7B3F61 0);
    z-index:2;
  }
</style>
```
