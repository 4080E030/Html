```html 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>熊貓問卷調查</title>
    
    <!--icon教學-->
    <!--icon為縮圖,logo的意思-->
    <!--他有一個屬性為rel,icon的標籤為shortcut icon-->
    <link rel="shortcut icon" href="./pandaIcon.png"/>
    <link rel="bookmark" href="./pandaIcon.png"/>
    </head>
<body>
```
   
```html        
        <!--Text教學-->
        <!--required placeholder為給使用者提示-->
        <label for="myname">姓名:</label>
        <input id="myname" type="text" name="InputName" required placeholder="請輸入真實姓名"/>
        <br/>
```
```html
            <!--radio教學-->
            <!--radio為選擇方塊-->
            <label for="gender">性別:</label>
            <input id="male" type="radio" name="gender" value="male">
            <label for="male">男性</label>
            <input id="female" type="radio" name="gender" value="female">
            <label for="female">女性</label>
            <input id="other" type="radio" name="gender" value="other">
            <label for="other">其他</label>
            <br/>
```
```html
        <!--select name教學-->
        <!--select name為下拉選單-->
        <!--required為必填區塊-->
        <!--option為內容物,第一個就是要讓預設為空白的所以沒有填其他東西-->
        <!--value為它的名稱-->
        <label for="gender">性別:</label>
        <select name="gender" id="gender" required>
        <option></option>
        <option value="male">男性</option>
        <option value="female ">女性</option>
        <option value="other">其他</option>    
        </select>
        <br/>
```
```html
            <!--一樣是text-->
            <!--只是id改為telephone,電話-->
        <label for="tele">電話:</label>
        <input id="tele"   type="text" name="telephone">
        <br/>
```
```html
            <!--email教學-->
            <!--email跟text不一樣是他一定要email的形式才能交出表單-->
        <label for="email">信箱:</label>
        <input id="email"   type="email"  name="email" placeholder="@..."/>
        <br/>
```
```html
            <!--age教學-->
            <!--value為預設值-->
            <!--min為最小值,max為最大值-->
            <!--placeholder為值-->
        <label for="age">年齡:</label>
        <input id="age" type="number" value="18" min="0" max="100" placeholder="0~100">
        <br/>
```
```html
            <!--datalist教學-->
            <!--datalist為下拉式選單-->
            <!--list內容預設為arelise-->
            <!--id預設為arelise-->
            <label for="area">地區</label>
            <input list="arealise" type="text" name="area" id="area">
            <datalist id="arealise">
                <option value="基隆市">基隆</option>
                <option value="台北市">台北</option>
                <option value="台南市">台南</option>
                <option value="苗栗縣">苗栗</option>
                <option value="彰化市">彰化</option>
                <option value="雲林縣">雲林</option>
                <option value="屏東市">屏東</option>
                <option value="新北市">新北</option>
            </datalist>
            <br/>
```
```html
       <!--password教學-->
       <!--type必須為password-->
       <!--minlength為最小值-->
       <!--maxlength為最大值-->
        <label for="password">密碼:</label>
        <input type="password" minlength="6" maxlength="20">
```
```html
        <!--hr為水平線-->
        <hr/>
```
```html
        <!--suggestion教學-->
        <!--for必須為suggestion-->
        <!--clos為寬,rows為長-->
        <label for="suggestion">網站留言:</label>
        <br/>
        <textarea name="suggestion" id="suggestion" cols="30" rows="10"></textarea>
        <br/>
```
```html
        <!--checkbox教學-->
        <!--for必須為Checkbox-->
        <!--checked/ 為只要使用者來這個頁面預設就會打勾起來-->
        <input type="checkbox" id="checkbox" name="news" vaule="" checked/>
            <label for="checkbox">訂閱熊貓電子報</label>
            <br/>
```
```html
            <!--range教學-->
            <!--range為範圍-->
            <!--我們預設為年齡,min為最小值,max為最大值,step為跳多大的數字-->
            <!--開頭的0和100就是最大值最小值要打在外面使用者才看的到-->
            0<input type="range" min="0" max="100"step="10">100
            <br/>
```
```html
            <!--file教學-->
            <!--file為檔案-->
        <input type="file" name="file">
        <br/>
```
```html
        <!--sumbit教學-->
        <!--訂閱,提交的意思-->
        <button type="submit">提交表單</button>
    </form>
</body>
```
```html
<!--div教學-->
    <div class="">
    <a href="http://www/google.com">google</a>
    </div>
    <div>
    <a href="./index.html">熊貓資訊網</a>
    </div>
    <div>
    <a href="http://www.youtube.com">Youtube</a>
    </div>
```
```html
<!--特殊符號教學-->
<h1>&#9841;</h1>
<h1>&#9857;</h1>
<h1>&#9861;</h1>

</html>
```
