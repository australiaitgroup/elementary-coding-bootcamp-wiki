# 第二課 HTML 重點

## 網頁包含了什麼?
  HTML: 像人的骨骼一樣, 包括整個網頁的內容  
  CSS: 像人的皮膚, 把網頁的內容進行包裝和佈局, 像是改變文字的顏色,大小  
  Javascript: 像是人的肌肉, 包括網頁上的行為 P.S. 老師在Javascript補充 實際可以做任何事情, 包括更改已有的HTML和CSS

## HTML基本語法&佈局
Element 由 < p style="color:red"> IT123 < /p> 組成  
  < p > 是一個Opening tag  
  style="color:red" 是一個屬性(Attribute)  
  IT123 是內容(Content)  
  < /p> 是一個Closing tag  
    
   記得在創建html檔時, 首行**必須**是< !DOCTYPE html> 去聲明這是一個HTML5檔案
   必須的tag可以詳細看lession2.pdf中的page6
   
## <head>中包含哪些?
  title, meta, link, style, script 也是放在<head>當中  
  在link當中, 如果要把外部的CSS顯示在這個HTML內, 必須寫上rel="stylesheet"  
  在script當中,要寫上Scr="..."  
  **留意** head中的內容不會顯示在網頁的內容內
  
## <body> 包含什麼?
  就想把你想顯示的內容放在body裡  
  例如: 表格, 圖片, 文字..etc
  
## Block Element vs Inline Element
  Block Element: 就是element的闊度是填滿整個頁面的, 所以當出現下一個element時是會換行  
  Inline Element: 就是element的闊度是有限制的, 只能填滿該element的內容闊度
  
## Link tag
  記得在< a>中加入target=" " 是可以控制該超連結的開啟方式(例如: _blank 就是可以打開一個新tab)
  
## Header h1-h6
  一個網頁 **只可以一個h1** 其餘的沒限制  
 原因是會影響在搜尋中的排名
  
## Text類
  在< p>內實現換行 記得是用< br> 不然沒效果
