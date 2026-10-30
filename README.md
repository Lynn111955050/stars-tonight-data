# 觀星App天象資料

這是獨立於App程式的公開天象清單，不含使用者位置或帳號資料。

更新sky_events.json並增加revision整數即可；schemaVersion保持1。保留事件id，修正日期或文字時不要換id；移除事件代表撤回。每筆需要id、title、kind、note、source、start、end，日期包含+08:00時區且end晚於start；請核對天文館或IMO來源。

清單由手機連線取得，失敗時沿用已保存版本，仍受手機系統排程及網路限制，非即時推播服務。不要放任何密碼、金鑰或個人資料。
