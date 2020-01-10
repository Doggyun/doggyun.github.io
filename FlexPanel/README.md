#  Flex Panel  #

##  **實現目標**  ##

實現使用者點擊任一張圖片，圖片會展開及文字動態的效果。
##  **Demo**  ##
<img src="img/FlexPanel.png" width="600" height="200"/>

##  **相關屬性**     ##

**Flex**

- flex-direction
- justify-content
- align-items


**transform**

- translateX
- translateY


**classList**

- add()
- remove()
- toggle()






# 過程中我遇到的困難 #

----------
**CSS**:

- Flex box 需要多練習才會比較熟練。

**Javascript**:

- forEach()是如何取Array的單筆資料且有序的呼叫callBack function執行 ?

## 解決方法: ##

這是在stackOverFlow上找到的解答，forEach()底層可能的運作方式:
        
     function callback(currentValue,currentIndex,listObj){
    // do something
    };   
    
    NodeList.prototype.forEach = function(callback) {
    for(let i = 0; i < this.length; i++) {            
    callback(this[i], i, this); //this指向NodeList
    }};                    
    NodeList.forEach(callback);
       

### 參考 ###
Wes Bos :[https://javascript30.com/](https://javascript30.com/) Day5