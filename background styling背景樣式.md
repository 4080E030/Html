# background-color
```css
跟html一樣
h1{
  background-color: crimson;
  color: white;
}
簡單一點也可以使用background就好了，vscode 裡面的background也代表background image 或是color
```
# background-image
```
body {
  background-image: url("./ying-wu-NsNRu6dfRds-unsplash.jpg");
}
後面的網址是我自己新增的所以如果要改的話記得上網找在貼上去
```

# background-size:cover;處理背景圖片的大小，cover下面有解釋
```css
/* 关键字 */ 最常使用為這兩個，如果要再讓圖片至中就要再使用 background-position: center; 會在下面講解
background-size: cover   他會把圖片放到最大直到你不是水平或是垂直，意思就是說會把圖片整個放到最大的頁面就對了
background-size: contain 這會把圖片放到最到如果還沒辦法把網站放到滿就會在repeat重複再放一個直到放滿

以下就是mdn裡面的範例
/* 一个值: 这个值指定图片的宽度，图片的高度隐式的为auto */
background-size: 50%
background-size: 3em
background-size: 12px
background-size: auto

/* 两个值 */
/* 第一个值指定图片的宽度，第二个值指定图片的高度 */
background-size: 50% auto
background-size: 3em 25%
background-size: auto 6px
background-size: auto auto

/* 逗号分隔的多个值：设置多重背景 */
background-size: auto, auto     /* 不同于background-size: auto auto */
background-size: 50%, 25%, 25%
background-size: 6px, auto, contain

/* 全局属性 */
background-size: inherit;
background-size: initial;
background-size: unset;
```
# background-position:center;/*or bottom or top*/ 處理背景圖片的位置，要先使用上面得background-size 再來用後續的 background-position 來調整圖片的位置
```css
 /* Keyword values */最常也是用到這些，例如上方、下方、左邊、右邊或是置中
background-position: top;
background-position: bottom;
background-position: left;
background-position: right;
background-position: center;

/* <percentage> values */
background-position: 25% 75%;

/* <length> values */
background-position: 0 0;
background-position: 1cm 2cm;
background-position: 10ch 8em;

/* Multiple images */
background-position: 0 0, center;

/* Edge offsets values */
background-position: bottom 10px right 20px;
background-position: right 3em bottom 10px;
background-position: bottom 10px right;
background-position: top right 10px;

/* Global values */
background-position: inherit;
background-position: initial;
background-position: revert;
background-position: unset;
```
