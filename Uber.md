# Uber 司機
## User story
上線接單時可以查看乘客距離等資訊，決定接哪一組乘客

## Acceptance criteria
### Given
司機想開始接單

### When
司機登入系統並開啟接單狀態(點按鈕之類的)

### Then
司機可以瀏覽附近等待叫車的乘客訊息(乘客人數、距離、特殊需求...)

### Given
司機確認接送乘客，開始訂單流程

### When
司機點擊乘客圖示，點擊確認接單

### Then
系統鎖定乘客狀態(已派單)，通知乘客司機資訊；
提示司機乘客位置

## User story
司機結束載客後，需要結算車資並給乘客評價

## Acceptance criteria
### Given
司機結束載客

### When
司機點擊"結束訂單"

### Then
系統結算訂單金額，司機與乘客確認後透過線上支付收款，並結束訂單

### Given
司機收到系統通知，詢問對乘客的評價

### When
司機點擊"結束訂單"後

### Then
司機填寫客戶評價並回傳


# Uber 乘客
## User story
需要乘車服務，尋找鄰近司機

## Acceptance criteria
### Given
乘客需要搭車服務

### When
乘客點開app，填入目的地位置

### Then
系統顯示鄰近可提供服務的司機；同時向鄰近司機更新乘客訊息

### Given
乘客與司機已確認訂單

### When
乘客確認司機且司機確認接單

### Then
系統向乘客更新司機位置，並提示候車地點；
系統向司機更新乘客位置，並提示候車地點

## User story
乘客於搭車過程中與司機發生糾紛，須報警處理

## Acceptance criteria
### Given
乘客與司機有乘車糾紛

### When
乘客點擊app通報緊急事件

### Then
系統紀錄通報時間，並連繫警政系統

## User story
乘客抵達目的地，結束訂單

## Acceptance criteria
### Given
乘客抵達目的地

### When
乘客點開app，確認金額與目的地點

### Then
乘客使用線上支付確認付款，並點擊完成訂單流程

### Given
乘客結束訂單後，收到系統訊息詢問對司機評價

### When
乘客接收到系統訊息

### Then
乘客提交司機評價

## User story
想要搭乘較高等級的車子

## Acceptance criteria
### Given
乘客在選取目的與車子的page

### When
車子的選項有不同等級的按鈕

### Then
選擇後地圖上僅會顯示該等級車子以供選取


## User story
希望可以選擇評價優良的司機

## Acceptance criteria
### Given
在進入到選擇車子的地圖上

### When
在點選車子看到車子的資訊

### Then
資訊內會包含司機本身的評價以供乘客參考選擇


