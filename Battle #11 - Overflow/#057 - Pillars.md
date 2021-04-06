# 57 - Pillars

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/57.png)

## My Solution

```
<div>
  <div class="black">
    <span class="yellow">
      <span class="blue"></span>
    </span>
  </div>
  <div class="black right">
    <span class="yellow">
      <span class="blue"></span>
    </span>
  </div>
  <div class="black rightbot">
    <span class="yellow">
      <span class="blue"></span>
    </span>
  </div>
  <div class="black leftbot">
    <span class="yellow">
      <span class="blue"></span>
    </span>
  </div>
</div>
<style>
  body{background:#191919}
  div {
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    width: 110px;
    height: 110px;
    background: #4F77FF;
  }
  .black{
    width:60px;
    height:60px;
    background:#191919;
    position:absolute;
    left:10px;
    top:10px;
    border-radius:50%;
  }
  .yellow{
    position:absolute;
    width:45px;
    height:45px;
    border-radius:50%;
    background:#F9E492;
  }
  .blue{
    position:absolute;
    width:30px;
    height:30px;
    border-radius:50%;
    background:#4F77FF;
  }
  .right{
    left:unset;
    right:-20px;
    top:-20px;
    transform:rotate(90deg)
  }
  .rightbot{
    left:unset;
    top:unset;
    right:-20px;
    bottom:-20px;
    transform:rotate(180deg)
  }
   .leftbot{
    left:-20px;
    top:unset;
    bottom:-20px;
    transform:rotate(270deg)
  }
</style>
```
