moedict-data-for-chewing-editor
===============================

g0v 將「重編國語辭典（修訂本）」的公眾授權內容處理為機器比較容易再利用的 json 格式後在 [g0v](https://github.com/g0v) / [moedict-data](https://github.com/g0v/moedict-data) 釋出，「moedict-data-for-chewing-editor」做的是利用 g0v 釋出的 json 格式「重編國語辭典（修訂本）」取辭彙及ㄅㄆㄇㄈ音標的部份轉換為 [新酷音輸入法](http://chewing.im/) 的 [詞庫編輯器](https://github.com/chewing/chewing-editor) 可以利用的格式，藉此使用者可以自行擴充新酷音輸入法的辭彙量，進而提升使用輸入法時的便利性。本辭典本文的著作權仍為教育部所有。

說明：
因授權因素，此處所做詞庫轉換不考慮預先過慮重疊新酷音現有詞庫的辭彙，轉換後的檔案分別為以下：

- moedit-for-chewing.json
- moedit-for-chewing.src.json

其中 **moedit-for-chewing.json** 是沒有經過縮排、排版的版本，而 **moedit-for-chewing.src.json** 是使用 2 格半形空白進行縮排的版本，前者檔案較小、便於傳輸，後者檔案較大、但便於使用者閱讀，兩者均為標準的 Javascript Object - JSON 格式，內容也均相同，使用者可以自行選擇要使用哪份檔案。

重編國語辭典公眾授權頁：http://resources.publicense.moe.edu.tw/dict_reviseddict_download.html

依教育部之解釋，「創用CC-姓名標示- 禁止改作 臺灣3.0版授權條款」之改作限制標的為文字資料本身，不限制格式轉換及後續應用。

    =====================================================
    編　　　輯　　　者：教育部國語推行委員會

    國語推行委員會主任委員：童春發

    編輯委員會主任委員：李　鍌

    總　　　編　　　輯：李殿魁

    副　總　編　輯　：曾榮汾


    發　　行　　人：杜正勝

    發　　行　　所：教育部

    地　　　　　址：臺北市中山南路5號

    電　　　　　話：(02)7736-6801
    =====================================================

此處轉換格式、重新編排的編輯著作權(如果有的話)由 @PeterDaveHello 以 CC0 釋出。
