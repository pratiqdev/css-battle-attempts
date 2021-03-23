# Target 10 - Cloaked Spirits

2021/03/10

![Target](https://cssbattle.dev/targets/10.png)

## 99.9% - 419 / 195

```css
<p><p><p><style>body{background:#62306d;display:flex;justify-content:center}p{height:1000px;border-radius:50px;background:#F7EC7D;margin-top:42px}p:after{border-radius:50%;display:block;content:'';width:100px;height:100px;background: radial-gradient(#AA445F 42%, #E38F66 43%)}p:nth-child(1):after,p:nth-child(3):after{background: radial-gradient(#E38F66 42%, #AA445F 43%)}p:nth-child(1),p:nth-child(3){margin-top:142px}
```

## Expanded

```css

```

## Original Answers

### 1 - 99.9%

The edges of the `p:after` do not exactly match the edges of `p`... Is this a side effect of psuedo-elements?

```css
<p><p><p>
<style>
 body{
    background:#62306d;
    display:flex;
    justify-content:center;
}
*, *:after{
    border-radius:50px
}
p{
    height:1000px;
    background:#F7EC7D;
  	margin-top:42px
}
p:after{
    display:block;
    content:'';
    width:100px;
    height:100px;
    background: radial-gradient(#AA445F 42%, #E38F66 43%);
}
p:nth-child(1):after,p:nth-child(3):after{
    background: radial-gradient(#E38F66 42%, #AA445F 43%);
}
  
p:nth-child(1),p:nth-child(3){
  	margin-top:142px;
}
```
