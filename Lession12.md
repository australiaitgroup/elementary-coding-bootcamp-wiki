# 第十二課 Javascript-3 重點內容
## 重點
### event(事件)
1. 所有在應用程式/網頁中的行為, 全部也是由JS的event去控制  
eg. 點擊, 滑動 etc  
步驟:  
1. 先使用querySelector/getElementsByClass etc方法選出需要的元素  
2. 再使用addEventListener的function去悿加需要監聽的Event  
3. 寫出所需的操作  
4. 同一個元素是可以悿加多個listener的!!  
5. 另一個方法是使用onevet <--記得on後面也是小寫  
### AJAX
Asynchronous JavaScript and XML(非同步的JavaScript與XML技術)  
1. 使用AJAX的意義: 可以減少任務時間, 也排除擠擁情況  
#### Asynchronous vs Synchronous
Synchronous(同步): 是把所有function/command 使用線性方式去運行, 意思是一個接一個完成, 所以耗時長  
Asynchronous(異步/非同步): 是把所有function/command**並行**運作, 意思是先把command/code運行,在不影響其他command的情況下運算結果, 之後再果結果返回給使用者  
在前端使用XMLHttpRequest與Server 通信  
包括2個指令  
1. open(urlMethod, url)<--提出你對server的要求get,post etx  
2. send() <---發出你所提出的要求  

