# bitget_合約帳戶明細API

**所有資訊皆已過時，bitget api已過渡到v2，請參考 [過渡指引](https://www.bitget.com/api-doc/common/release-note)**

基於google sheet的app script，可以直接利用Bitget自帶的api自動抓取合約交易 開倉關倉 做多做空的時間點、利潤、手續費、交易量，沒有任何交易功能

<img src="https://user-images.githubusercontent.com/24865458/154845599-ae553e9e-ecbe-4acf-8332-f55940795986.png" width="50%">

## 第一步:申請API

<img src="https://user-images.githubusercontent.com/24865458/154844906-09d00271-70d9-452d-ae4e-479df442d785.png" width="50%">

右上角點擊API管理，如果沒有綁定google authenticator的這時候會要求你綁定

<img src="https://user-images.githubusercontent.com/24865458/154845011-ddeab17d-cb12-4abd-a4c1-f8b65b20490d.png" width="50%">

passphrase的部分很像密碼，在此處輸入後就不會再出現，須牢記

 權限方面建議不要將交易打開，以免有財產被盜走的風險存在，ip那格請留白，不要有任何ip的限制

 接著下一步後可以得到三個東西，apikey, secretkey, passphrase

 apikey:類似於你的api的帳號

 secretkey:非常重要，加密的鑰匙

 passphrase:類似於你的api的密碼
 
## 第二步:建立google sheet的副本

https://docs.google.com/spreadsheets/d/1ykDxYzQgo47Dquxjiep8bJs72wooCtWLTIy88zJRpEE/

點選左上角建立副本，你可以得到一份試算表出現在你的雲端硬碟

## 第三步:填入內容

此處就兩個部分需要填入

### 所需的時間區間

<img src="https://user-images.githubusercontent.com/24865458/154845414-cee6028c-40ae-4fda-837f-4e02594ed0b8.png" width="50%">

### 你的apikey,secretkey,passphrase

<img src="https://user-images.githubusercontent.com/24865458/154845538-a2d058a2-4d23-4b91-a089-d3e2a9c00489.png" width="50%">

## 可能會遇到的問題

### 1.未開放權限，請放心地按下允許

<img src="https://user-images.githubusercontent.com/24865458/154935431-055132b4-e84b-4dd7-83ff-10b48e41d5fc.png" width="50%">
