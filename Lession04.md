# 第四課CSS內容重點:
## 前端設計心得
老師分享一些心得關於前端的設計思路  
分析每一個session, 由上到下, 左到右去想, 需要想得仔細

## CSS Specifity
就是在CSS中selector的優先級  
id永遠是最大優先級  
class是其次  
tag是最低 (* 基本就是0優先, 最容易被取代)

## Box Model
同學必須了解 width x height , padding, border, margin是如何構成 **經典結構,超重要**  
重播位置: 32:00左右 (有需要的同學可以再聽重播)  
width x height 實際內容的大小  
padding 內容與border之間的空間  
border 邊框  
margin 邊框外的空間  
留意margin collapsing (就是上下/左右的margin會疊加而不是相加)

## Position
記得如果要使用absolute, 需要在前一層寫上position:relative, 否則absolute會根據頁面大小去定位

## float
避免用作佈局, 減少不確定性, 用flexbox作佈局  
grid兼容較flexbox弱, 而且flexbox可以完美代替grid (yeah~) 
