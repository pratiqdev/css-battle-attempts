# Target 1 - Simply Square

2021/03/10

![Target](https://cssbattle.dev/targets/1.png)

## 100% - 54 / 54

```css
<a style=box-shadow:0+0+0+2in#b5e0ba,0+0+0+5in#5d3a3a>
```

## Expanded

```css
<a>

<style>
a{
    box-shadow:
        0 0 0 2in #b5e0ba,
        0 0 0 5in #5d3a3a;
}
```

Seen in the wild.

A single element is required for this battle: a paragraph element could be used (p is default block level el / anchors are inline).
The single element is 0 x 0 px, and has a two box shadows with fixed sizes.

Ems can be used instead of inches at the cost of 3 extra characters due to large number of ems required to match inches.

## Original Answers

```css
<p><style>*{background:#5d3a3a;margin:0}p{width:200px;height:200px;background:#B5E0BA
```
