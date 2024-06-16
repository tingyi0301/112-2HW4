# 第4次作業-作業-HW4
>
>學號：111108116
><br />
>姓名：吳亭誼
><br />
>作業撰寫時間：30 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2024/06/09
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x] 說明內容
- [x] 個人認為完成作業須具備觀念

## 說明程式與內容
</br>(a)初步類別圖
</br>![alt text](a.png)

(b)
</br>![alt text](b1.png)
</br>合約1：bindUser()
</br>操作：bindUser(name,phoneNumber)
</br>交互參照：綁定住戶手機
</br>前置作業：住戶提供姓名、手機號碼綁定APP
</br>後製作業：與警衛確認完後於APP顯示綁定成功

</br>![alt text](b2.png)
</br>合約2：updatePackage()
</br>操作：notificationReceived(name,receivedTime,address)
</br>交互參照：包裹領取通知
</br>前置作業：警衛簽收包裹
</br>後製作業：包裹所屬人之住戶獲得APP推播簡訊，包含收件時間與幾號幾樓住戶

</br>![alt text](b3.png)
</br>合約3：createAnnouncement()
</br>操作：createAnnouncement(content,contentBy)
</br>交互參照：委員發佈公告
</br>前置作業：由委員發出公告
</br>後製作業：公告成功發佈，其他住戶可查看

</br>![alt text](b4.png)
</br>合約4：addResponse()
</br>操作：addResponse(content,user)
</br>交互參照：住戶回應公告
</br>前置作業：用戶已綁定
</br>後製作業：新增回應成功

</br>![alt text](b5.png)
</br>合約5：editAnnouncement()
</br>操作：editAnnouncement(content)
</br>交互參照：委員修改公告
</br>前置作業：針對已發佈公告進行修改
</br>後製作業：修改成功


## 個人認為完成作業須具備觀念

參照topic 5、6繪製初步類別圖及系統循序圖，了解步驟和圖形物件基本使用概念後大概先畫框架出來。