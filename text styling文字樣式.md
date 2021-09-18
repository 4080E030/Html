# text styling文字樣式
##  1.font size (units in CSS,relative and absolute:px,rem)
```
我們參考w3shool:https://www.w3schools.com/css/css_units.asp 

font size 有兩種類型的長度單位：絕對和相對。
cm	centimeters
mm	millimeters
in	inches (1in = 96px = 2.54cm)
px *	pixels (1px = 1/96th of 1in) 常用到 也是中文的像素
pt	points (1pt = 1/72 of 1in)
pc	picas (1pc = 12 pt)

``` 
## 2.text-align (文字置中,靠左,靠右那類的)
```css
  p{
    text-dercoration:line-through;        字中間有橫線的
   }
    dercoration                           裝飾的意思
 
  a{
     text-decoration: none;               把a這個變色 我們的a也是youtube,google的網址可以使那個變色
     color:coral;  
   }
```
## 3.text-decoration(underline,none,line-throught)
```css
 p{
    text-dercoration:underline;           底線
   }
```
## 4.line-height(行高)
```css
/* Keyword value */
line-height: normal;

/* Unitless values: use this number multiplied
by the element's font size */
line-height: 3.5;

/* <length> values */
line-height: 3em;

/* <percentage> values */
line-height: 34%; 

/* Global values */
line-height: inherit; (繼承，之前設定好的值可以直接使用inherit)
line-height: initial;
line-height: revert;
line-height: unset;
```
```
https://developer.mozilla.org/en-US/docs/Web/CSS/line-height
```
## 5.letter spacing(字的距離,格多遠)
```css
/* Keyword value */
letter-spacing: normal;

/* <length> values */
letter-spacing: 0.3em; 
letter-spacing: 3px;
letter-spacing: .3px;

/* Global values */
letter-spacing: inherit;
letter-spacing: initial;
letter-spacing: unset;
```
```
https://developer.mozilla.org/zh-CN/docs/Web/CSS/letter-spacing
```
## 6.font-family(lt's safer to use a font stack,which is an order of fonts.)(字體)
```html 
如果想測試字體的話可以使用 
<p>lorem 10 <p> 或是20 以此類推，如此一來就可以產生一些英文字，但那算是亂碼可以用來測試字體的

 EX:<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi minus obcaecati fugit dolor, quibusdam reprehenderit facere sint suscipit quas 
    voluptates! Sequi blanditiis voluptatibus iste obcaecati, repellat error debitis labore ad.</p> 
後面再去到CSS裡面 
p{
font-family: 'Courier New', Courier, monospace;     後面的'Courier New', Courier, monospace;可以自行挑選看自己喜歡什麼自己可以去看看
}
這網址是可以看在什麼作業系統所擁有的字體:
```
```
https://www.cssfontstack.com/
```
## 7.text-indent (字前面的空格)
```
``` 
