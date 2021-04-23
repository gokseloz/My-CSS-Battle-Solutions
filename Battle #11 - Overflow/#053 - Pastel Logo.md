# 53 - Pastel Logo

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/53.png)

## My Solution

```
<div></div>
<div></div>
<style>
  body{margin:0;background:#19191A}
  div {
    position:absolute;
    top:50px;
    left:50%;
    transform:translateX(-50%);
    width: 150px;
    height: 150px;
    background: #4F77FF;
    border-radius:50%;
  }
  div:nth-of-type(2){
    width:75px;
    height:125px;
    background:radial-gradient(circle at 100% 0%, #9AD5FF 0 51.5%, #F9E492 0%);;
    border-radius:0;
    transform:none;
    left:125px;
    top:125px;
  }
</style>
```
