# 第三課 CSS 內容重點(包含一部分第二課HTML內容):
## img類
盡量要在img tag內寫上一個 alt=" " 可以在圖片無法顯示時, 顯示這是一個關於什麼的圖片

## Absolute path 和 Relative path
1.在寫項目時一般會用relative path, 因為可以用更短的路徑顯示  
2.如果項目最終是會在服務器上運行而不是在開發人員的電腦, 寫上absolute path就無無法顯示出該文件內容

## 什麼是好的HTML?
1. 就是要所有tag也是需要有意義, 用得其所。從而令到其他開發人員也能容易閱讀
2. 緊記不能只方便自己閱讀

## CSS
CSS - Cascading Style Sheets  
意思是說是一種級聯式的東西  
想像是從上到下去閱讀每一行, 而相同的東西會被至下面位置的所取代  

## 3種在HTML中插入 CSS
External < Internal < Inline CSS是一有優先級的, 其中Inline是最高但必須盡量避免 使用 
盡量把所有CSS style寫在external css sheet當中  

## Chrome Devtool
是一個超級好用的東西, 記得盡量使用chrome當瀏覽器  
我們可以在一個網頁當中right click > inspect(檢查) > element中可以看到這頁面的HTML, style 可以看到這頁面的CSS  
我們也可以在這裡修改一些css/html去看實際效果, 但refreash後一切還原

## Selector
基本有3種, 1.使用tag 2. 把tag加上id(使用#idname) 3. 把tag加上class(使用.classname)  
記得一個id只能使用一次, class可以無限制使用  
**老師再三強語: 所有命名必須有意義**

## CSS Reset
**老師強調**這是一個面試的考點, 加分項  
必須習慣在項目中加入一個 reset.css / Normalize.css 
原因: 每一種瀏覽器的預設element也不一樣!!!
