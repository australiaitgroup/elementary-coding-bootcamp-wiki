# 第十一課 Javascript-2 重點內容

## 重點
0, ' ' , undefined, null, [] {}, false 在js中是等價的(是一種特性, 面試有機會問)  
### Function
Function最重要功能 - 可複用性  
所有return 以下的語句也不會被運行  
if condition 如果只是對/錯 沒有中間選擇的, 可以選擇忽略else  
Scope(作用域)(**重要, 要清楚了解,面試有機會問到**)  
Globe Scope = 全局域, 整個JS中也一直存在, 自由讀取  
Local Scope(Variable) = 局部域(變量), 只是在該function中使用, 外部無法讀取  
Hoisting 是JS的特性, 在function內也存在

### Object
非常常用的複合類型的值,也是JS的核心概念  
用{}括起來  
this. 的用途很多, 其中一個是返回該object中local的值, 另外可以避免改變外部的value  
如果不同變量指向同一個對象, 當修改變量時是會影響所有變量

### DOM (Document Object Model)
通過使用 document.querySelector 可以把HTML的東西給抓出來  
querySelectorALL 就可以把一樣的全部抓出來, 這樣就會像Array一樣, 所以可以用[0,1,2,3..etc]給抓想要的element出來  
  
  有homework呀!! 同學記得做! 老師會有回饋!  
  DOM作業 概念可以在課堂大概 2:43:00左右 看一下! 同學加油!!  
  JA作業  概念可以在課堂大概 2:50:00左右 看一下!
