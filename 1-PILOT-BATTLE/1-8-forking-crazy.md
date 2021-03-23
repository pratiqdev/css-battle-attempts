# Target 8 - Forking Crazy

2021/03/10

![Target](https://cssbattle.dev/targets/8.png)

## 100% - 576 / 156

```css
<i><p><p><p><p><p><p><p><style>body{margin:0;border:190px solid #6592CF;height:999px;background:#060F55;}p{display:inline-block;margin-top:-90px;height:90px;width:20px;background:#6592CF}p::before, p::after{display:block;content:'';height:20px;width:20px;border-radius:50%;margin-top:-10px;background:inherit}p::after{margin-top:70px;}p:nth-child(1),p:nth-child(3),p:nth-child(5),p:nth-child(7){background:#060F55}i{top:150px;right:130px;position:absolute;display:block;background:#060F55;width:140px;height:100px;border-bottom-left-radius:70px;border-bottom-right-radius:70px
```

This was a tricky one :) Some psuedo elements make it easier

## Expanded

```css
<i>
<p>
<p>
<p>
<p>
<p>
<p>
<p>

  
<style>
body{
    margin:0;
    border:190px solid #6592CF;
    height:999px;
    background:#060F55;
}
  
p{
    display:inline-block;
    margin-top:-90px;
    height:90px;
    width:20px;
    background:#6592CF;
}

p::before, p::after{
    display:block;
    content:'';
    height:20px;
    width:20px;
    border-radius:50%;
    margin-top:-10px;
    background:inherit;
}

p::after{
    margin-top:70px;
}
  
p:nth-child(1),
p:nth-child(3),
p:nth-child(5),
p:nth-child(7){background:#060F55;}

i{
    top:150px;
    right:130px;
    position:absolute;
    display:block;
    background:#060F55;
    width:140px;
    height:100px;
    border-bottom-left-radius:70px;
    border-bottom-right-radius:70px;
}
```
