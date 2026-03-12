# 程式語言
## Chapter 1 初探
---
    - 能力金字塔 
    - 解決真實問題思維
    - 系統設計/需求定義/架構判斷
    - 程式閱讀/除錯/邏輯分解(人+AI)
    - 語法/樣板程式碼/API查詢(AI可以做的)
---
## 學習重點
-     了解why,how
- 增強表達想法的能力

    透過新程式語言結構擴大開發思維          
-   增進選擇合適程式語言的能力:

    熟悉的程式語言不一定適合本專案開發
    如果可以熟悉更廣的程式語言結構,即可更好的選擇具有最能解決問題的語言
-     增強學習新語言的能力
-     理解程式語言如何被實作而帶來的好處
-     更有效使用已知的程式語言
-     對電腦計算全面進步
---
## 程式設計領域
- 科學應用
   大量的浮點數運算:Fortran
- 商業應用
   產生詳細報告,十進制算術運算能力,數字和字元精確表示:COBOL
- 人工智慧
    以符號計算為主,而不是數值計算:LISP,Python
- 網頁軟體
    由多種語言支持:HTML,JavaScript,CSS
---
## AI 推進之父
    Hicton
---
## 程式語言評估準則
- 可讀性(Readability):程式被閱讀與理解的難易度
    - 在軟體生命週期中,維護成本>開發成本,而決定性關鍵在於可讀性
    - 整體簡潔(Overall Simplicity):
        - 特徵多樣性(feature multuplicity)最小化 
        - 運算符重載(operator overloading)最小化:一個運算符號有多個含意
        - 正交性(Orthogonality):透過副作用判斷程式的正交性 
        - 資料型態(Data Type):足夠的事先定義的資料型態
        - 語法設計(Syntax Design): 特殊字構成複合敘述的方法
- 可寫性(Writability):語言被拿來創建程式的難易度
    - 簡潔與正交性(Simplicity and Orthogonality)
    - 表現力(Expressivity)
- 可靠性(Reliability):符合規範(按照標準執行)
    - 型態檢查(type checking)
    - 例外處理(Exception Handing)
    - 別名使用(Aliasing)
    - 可讀性與可寫性(Readability and Writability)
- 成本(Cost):最終總成本
    - 訓練程式設計者使用該語言
    - 使用該語言撰寫程式(部分取決於特定應用程式的接近程度)
    - 執行程式
--- 
## 其他評估準則
- 可攜性(Portability):遷移不同系統,設備的難易度
- 通用性(Generality):適用於廣泛應用程式
- 明確性(Well-Definedness):語言官方定義的完整性與精確性
---
## von Neumann Architecture
- 資料與城市都儲存在記憶體
- 執行指令的中央處理器
- 指令與資料必須從記憶體傳輸到CPU
- CPU中的運算結果必須移回記憶體
---
    問題>記憶體>CPU>記憶體>答案   
---
## 程式設計的方法論
- 1950-1960
    - 關係機器的效率,低階機器語言
- 1960-1970
    - 硬體成本降低,程式設計者成本增加
    - 人員效率變得很重要,更好的可讀性與控制結構
    - 結構化程式設計(Structured Programming)
    - 程序導向(Procedure-Oriented)
- 1970-now
    - 程序導向到資料導向(Data-oriented)
    - 資料抽象化(Data Abstraction)
- 1980-now
    - 物件導向程式設計(Object-Oriented Programming)
    - 資料抽象化(Data Abstraction)+繼承(Inheritance)+多型態(Polymorphism)
---
## 程式語言分類
- 指令式(Imperative)
- 函式
- 組合式 
---
## 程式語言設計的取捨
- 可靠性與執行成本
- 可讀性與可寫性
- 可寫性(靈活度)與可靠性
---
## 程式語言實作方法
- 編譯
        
    將高階城市翻譯成機器語言

    特色:翻譯慢,執行快

    - 詞法分析器(Lexucal Analyzer)

            將原始碼中的字符轉換為詞法單元
    - 語法分析器(Syntax Abalyzer)
            
            將詞法單元轉換為語法解析樹
    - 語意分析器(Semantic Analyzer)

            檢查錯誤並產生中間代碼
    - 代碼產生器(Code Generator)

            產生機器碼
- 純直譯

    為程式提供一個虛擬機器實時更新結果

    - 優點
        
            容易實施原始碼的除錯,因為錯誤訊息可以很容易地指出錯誤
            原始碼可攜性相對高
    - 缺點

            執行速度比顛一程式語言慢很多,因為高階語言敘述的解碼比機器語言複雜
            
- 混合實作系統

        將高階語言翻譯成易於直譯的中間語言(Intermediate Code)
        比純執意更外 因為原始碼只須備解碼一次
        例如:JAVA
### 前置處理器(Preporcessor)


    
    
    
