# reserved color 
```html
也是我們最常見的
p {
  color: lightslategray;
}
使用性很方便，但是只有140種選擇可以使用
```
# rgb
```html
這個就是我們使用的rgb程式碼

h1 {
  color: rgb(0, 0, 0);
}
(0,0,0) 代表得是red,green,blue 
三個數字都是介於0~255種 如果都是0，代表就是黑色
如果是(255,0,0)就是紅色以此類推 
```
```
顏色的話可以參考:https://www.w3schools.com/cssref/css_colors.asp(顏色分類)
那如果想使用RGB可以參考:https://www.w3schools.com/colors/colors_rgb.asp(RGB color)
```
# rgba
```html
Rgba也就是透明度

h1 {
  color: rgb(0, 0, 0,1);
}
最後的1也是Rgba，可以介於0~1之間。0的話也就是空白了
```
# hex color
```html 
hex color也是16進制
跟一般的 reserved color 一樣只是我們可以去google找 hex color 裡面找到說他的代碼是多少
Hex color :https://www.google.com/search?q=hex+color&rlz=1C1ONGR_zh-TWTW957TW957&oq=hex+color&aqs=chrome..69i57j0l9.6872j0j4&sourceid=chrome&ie=UTF-8
找到下面的 #4287f5 然後複製到css 裡面
變成
h1 {
  color: #4287f5;
}
這樣就能顯示了
也可以參考:https://coloors86.netlify.app/
```
