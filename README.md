# HTML
本文本是用来记录学习HTML过程中的一些常用技巧， 从Udacity开始，然后会逐步添加

## Responsive
1. 修改viewport `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
2. Make things relative, e.g. `width: 100%`
3. media query: 
> 第一种需要多个文件
`<link rel="stylesheet" media="screen and (min-width: 500px)" href="yes.css">`
> 第二种需要在一个文件里多内容
```
@media screen and (min-width: 500px) {
  body { background-color: green; }
}
```
