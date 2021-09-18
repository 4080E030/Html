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
  p{
    text-dercoration:underline;           底線
   }
  a{
     text-decoration: none;               把a這個變色 我們的a也是youtube,google的網址可以使那個變色
     color:coral;  
   }
```
## 3.text-decoration(underline,none,line-throught)
## 4.line-height(行高)
## 5.letter spacing(字的距離,格多遠)

## 6.font-family(lt's safer to use a font stack,which is an order of fonts.)(字體)
```html 
如果想測試字體的話可以使用 
<p>lorem 10 <p> 或是20 以此類推，如此一來就可以產生一些英文字，但那算是亂碼可以用來測試字體的

 EX:<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi minus obcaecati fugit dolor, quibusdam reprehenderit facere sint suscipit quas voluptates! Sequi blanditiis voluptatibus iste obcaecati, repellat error debitis labore ad.</p> 
後面再去到CSS裡面 
p{
font-family: 'Courier New', Courier, monospace;     後面的'Courier New', Courier, monospace;可以自行挑選看自己喜歡什麼自己可以去看看
}
這網址是可以看在什麼作業系統所擁有的字體:
https://www.cssfontstack.com/
```
## 7.text-indent (字前面的空格)
```
``` 
