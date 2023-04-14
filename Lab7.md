# Lab7 - 清除測試容錯移轉

- 回到復原方案，點選「清除測試容錯移轉」<br>
  ![GITHUB](images/cleanuptestfailover-1.png "cleanuptestfailover-1")<br>
- 勾選「測試已完成。請刪除測試容錯移轉虛擬機器。」<br>
  ![GITHUB](images/cleanuptestfailover-2.png "cleanuptestfailover-2")<br>
- 回到資源群組 asr-rg，可以發現虛擬機器確實已經被刪除，但另外設定的流量管理員、應用程式閘道、堡壘等服務依然會存在，這些服務會讓您遭遇到正式容錯移轉時，有效的降低復原目標時間。<br>
  ![GITHUB](images/cleanuptestfailover-3.png "cleanuptestfailover-3")<br>
