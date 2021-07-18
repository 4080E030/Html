# 選擇器可以定義某組 CSS 樣式要套用到哪些元素上。
## Universal Selector
```html
* {
  color: green;
}
米字號可以讓全部的網站都變成你要變成的樣式
例如我設定成 color:green; 就代表說我網站內的文字都會變成綠色
```
## element Selector 
### element Selector 標籤的意思 也跟tag一樣
```html
這個element Selector 也是我們最常用的，例如 
h1 {
color:green;
} 
就是我們所謂的element Selector
```
## id Selector 
### id 也跟我們身分證一樣獨一獨二，也代表說 如果這一個h1我想要紅色 但是我其他h1想要藍色 我可以單獨把一個改成紅色 
```html
要先到你html的地方 例如:
<h1 id="RedText">學貓問卷調查</h1>
正常我們是 
<h1>學貓問卷調查</h1>
我們要先設立一個ID 才能把她改成你想要的，再到外部的CSS 
#RedText {
  color: red;
}
前面要加 #
```
## class Selector 
### class類別的意思 class 跟ID一樣要設定他的ID是什麼
```html
所以我們到html裡面設定，例如
<h2 class="blueText">&#9841;</h2>
<h2 class="blueText">&#9857;</h2>
<h2 class="blueText">&#9861;</h2>

一開始是<h2>&#9841;</h2>
加個類別後回到外部的CSS裡面
class 都是使用 .開頭，例如
.blueText {
  color: blue;
}
也可以改變字的大小，例如
<h2 class="blueText largeText">&#9841;</h2> 我們如果要一次加兩個以上的ID就直接空格加在class後面就好了
css裡面為 
.largeText{
  font-size: 3rem;
}
font-size 為字的大小

還有例如有一個<h1> 和一個<p> 兩個的class都一樣，我們也可以單獨改屬性，例如
<h2 class="blueText">&#9857;</h2>
<p class="blueText">&#9861;</p>  
  一個為h2一個為p
 在Css裡面我們就使用
h2.blueText{
  color: blue;
}
p.blueText{
  color: blue;
}
```
## Grouping Selector 
```html
```
## Descendant Selector 
```html
```
## (mixed Selector)
```html
```
## Attribute Selector 
```html
```
## Pseudo Class 
```html
```
## Pseudo Element 
```html
```
