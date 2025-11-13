# monster-data


📘 指令列表
```
🟦 Telegram 指令列表
指令	說明
/k 名稱	記錄怪物擊殺時間（使用當下時間）
/k 名稱 0800	使用自訂擊殺時間（0800 或 08:00）
/list	查看所有怪物擊殺紀錄（文字版）
/d 名稱	刪除某怪物的擊殺紀錄
/jobs	查看所有排程
/reload	重新載入 CSV 與週怪排程
/monsters	顯示怪物清單
/start	顯示所有指令說明
```

```
🟪 Discord 指令列表（僅限指定頻道）
指令	說明
!k 名稱	使用現在時間紀錄擊殺
!k 名稱 0800	自訂擊殺時間
!list	美觀版清單（embed 卡片）
!lt	表格格式查看擊殺紀錄
!d 名稱	刪除某怪物紀錄
!jobs	查看排程
!reload	重新載入 CSV 與排程
!monsters	查看怪物清單
```


📗 CSV 格式教學
```
monsters.csv
name	respawn_minutes	location	aliases
飛龍1	240	飛龍谷	小飛龍1|dr1
weekly_monsters.csv
name	weekday	time	location
巨蟻女皇	1,2,3,4,5	1700	螞蟻洞窟

含義：

weekday：0=Mon, 6=Sun

time：HHMM 或 HH:MM
```