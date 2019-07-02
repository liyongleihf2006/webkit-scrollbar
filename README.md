# webkit-scrollbar
chrome中自定义的滚动条样式,后面很多项目可能用到,先记录下来

```css
::-webkit-scrollbar{
  width:6px;
  height:6px;
}
::-webkit-scrollbar-thumb{
  border-radius: 4px;
  background-color:rgba(144,147,153,.3);
}
::-webkit-scrollbar-thumb:hover{
  background-color: rgba(144,147,153,.5);
}
```
