<!--
 * @Date: 2020-04-18 12:19:43
 * @LastEditors: wuzhe
 * @LastEditTime: 2020-04-19 17:20:43
 * @FilePath: c:\workspace\repository-everyday\wz-ui\README.MD
 * @Description: 
 -->
# DIY UI
## 目录结构
## 笔记
1. 想在键盘上直接提交搜索操作，如果想达到这种效果，就必须使用下面这种结构：    
```html
<form action="#">
    <input type="text" />
</form>
```
也就是带有 action 属性的表单里包含的 input 元素，这样的结构就会被输入法认定为表单的功能，会在键盘上显示出“前往”的按钮    

2. :valid伪类选择器，表示内容验证正确的input或其他form元素。:valid是和 input 中的“required”属性对应的，input 元素有内容时“required”验证条件就会通过，这时候 :valid 选择器就会选中这个 input。
