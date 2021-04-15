# 67 - Video Reel

## Target

![CSS Battle Challenge](https://cssbattle.dev/targets/67.png)

## My Solution

```
<div class="width45 pattern1"></div>
<div class="line"></div>
<div class="width140 pattern2"></div>
<div class="line"></div>
<div class="width140 pattern1"></div>
<div class="line"></div>
<div class="width45 pattern2"></div>
<style>
  body{margin:0;background:#191919;display:flex;}
  div{
    height:100%;
  }
  .width45{
    width:45px;
  }
  .width140{
    width:140px;
  }
  .pattern1{
    background:linear-gradient(#191919 0 26.8%,#5DBCF9 26.8% 40%,#191919 40% 76.8%, #5DBCF9 76.8% 90%, #191919 0% );
  }
  .pattern2{
    background:linear-gradient(#191919 0 10%,#5DBCF9 10% 23.3%,#191919 23.3% 60%, #5DBCF9 60% 73.2%, #191919 0% );
  }
  .line{
    width:10px;
    background:#5DBCF9;
  }
</style>
```
