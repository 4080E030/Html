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
Grouping Selector 跟前面的element Selector 類似只是變得方便比較多可以利用，來分開，一次寫完你要的樣式
h1,
h2{
  color: blue;
}
也可以加入P例如
h1,
h2,p{
  color: blue;
}
就是都加入一個逗點
```
## Descendant Selector 
### Descendant 後裔的意思
```html
使用Descendant Selector  要先使用之前交到的div 我們把網址的部分 分類到div的位置，例如
    <div class="link1 ">
    <a href="http://www/google.com">google</a>
    <a href="http://www.youtube.com">Youtube</a>
    </div>
    
    <div class="link2">
    <a href="./index.html">熊貓資訊網</a>
    </div>
然後div的部分都要新增class="" 裡面的ID看你要設定什麼，後面回到CSS設定說
    div.link1 a{
    color: red;
    }
  div是因為我們在div裡面然後選擇 link1 在選擇它裡面的a 顏色要改成red
    div.link2 a{
    color: blue;
    }
```
## (mixed Selector)
```html
```
## Attribute Selector 
```html
我們之前教的是一個一個設class="redText" 然後再去css裡面設定說redText{color:red;}
但是如果我們這樣設定就要一個一個設定了沒辦法一次設定很多個
所以我們直接找到input然後一定要是type="text" 這樣子我們在裡面輸入的字才可以顯示別的顏色
input[type="text"] {
  color: blue;
}
```
## Pseudo Class 
### Pseudo P不發音 是假的的意思 class為類別
```html
textarea:hover{
  background-color: blue;
} 
這個程式碼是 當我們滑鼠移到textarea，backgroung-color會變成blue
hover也是我們滑鼠的意思
我們使用下面這個作範例
input[type="text"] {
  color: blue;
後面可以加:hover 或是active 或是focus
hover也是滑鼠移過去就可以變那個顏色，active則是按著的時候可以變成那個顏色，focus則是按一下就可以了等按另一個就會變回去了

還有另外的像是tr標籤 就是我們所謂的表格也可以使用
tr:nth-child(2) {
  color: red;
} 這個是讓你的表格第2行第4行都會變成紅色
```
## Pseudo Element 
```html
Pseudo Element 是個可以一次性的來幫你加一些符號或是其他想加的文字
例如:
P::before {
  content: ">>";
  color: red;
}
這樣子就會在我們的P前面加入你想加的東西，顏色你也可以自己更改 before也是前面的意思
範例2:
h1::after{
  content: "↕	";
  color: red;
}
after則是在前面

p::first-letter {
  font-size: 2.5rem;
} 
first-letter則是第一個字
  font-size則是字會放大幾倍 2.5就2.5倍
```
