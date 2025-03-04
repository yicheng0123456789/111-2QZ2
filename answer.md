# 第2次隨堂-隨堂-QZ2
>
>學號：110111239
><br />
>姓名：游翊丞
><br />
>作業撰寫時間：180 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2023/05/26
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x] 說明內容
- [x] 個人認為完成作業須具備觀念

## 說明程式與內容

非西醫院欲透明顯示醫院內每間診間於各時段的主治醫生、護理師以及該時段主治醫師的病人名單。請同學參考投影片Topic 3 p. 37，寫出利害關係人與目標表。以下為討論隨筆簡述：

1. 非西醫院內有許多診間，每間診間擁有時段(e.g., 如某日的上午、下午)，在每個時段內有份該診間時段的顯示病人的治療名單。
2. 非西醫院內有許多醫師與護理師。在每個診間內的時段內，只有一位醫師作為主治醫師與一位護理師待在一間診間內。
3. 在每間診間的各時段內的顯示病人的治療名單上，需列出所有的病人。
4. 醫生與護理師屬於編制人員。
5. 病人非編制人員。
6. 編制人員與非編制人員都來自於人員名單。

    答案：
    |利害關係人<br >(參與者)|目標|
    | ---- |---- |
    |醫生工作項目|診斷和治療疾病|
    |護士工作項目|提供基礎醫療護理，協助診斷和治療
    |病人項目|醫療照護，配合治療
    |醫院院長工作項目|處理醫療事務，培養醫療人才

開始寫說明，該說明需說明想法，
並於之後再對上述想法的每一部分將程式進一步進行展現，
若需引用程式區則使用下面方法，
若為.cs檔內程式除了於敘述中需註明檔案名稱外，
還需使用語法` ```語言種類 程式碼 ``` `，其中語言種類若是要用python則使用py，java則使用java，C/C++則使用cpp，
下段程式碼為語言種類選擇csharp使用後結果：

```csharp
public void mt_getResult(){
    ...
}
```

若要於內文中標示部分網頁檔，則使用以下標籤` ```html 程式碼 ``` `，
下段程式碼則為使用後結果：

```html
<%@ Page Language="C#" AutoEventWireup="true" ...>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" ...>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
        </div>
    </form>
</body>
</html>
```
更多markdown方法可參閱[https://ithelp.ithome.com.tw/articles/10203758](https://ithelp.ithome.com.tw/articles/10203758)

## 個人認為完成作業須具備觀念

開始寫說明，需要說明本次作業個人覺得需學會那些觀念，亦可作為學習筆記使用 (需寫成文章，需最少50字，並且文內不得有你、我、他三種文字)
類別圖是一種用於可視化類別之間關係的結構圖，它描述了類別的屬性、方法和它們之間的關聯。類別圖提供了一個清晰的概覽，幫助開發者設計和理解軟件系統的結構和行為。