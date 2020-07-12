# js-websocket-chat
一個簡易的聊天室

首次嘗試利用websocket製作一個可以多人同時線上對話的聊天室。

下載後，進到本機的專案資料夾下的server資料夾，然後輸入`node server.js`。

```
Listening on 3000
```

看到這段，就表示已開啟本地端server。

這時候再打開client的index.html於瀏覽器上，同時打開開發著工具的console。
如果看到`open connection`就表示成功連線。

建議可以同時開兩個index.html視窗，然後試著互相對話看看。

---

server端
使用node.js的express跟ws

ws -> websocket

---

client端
當送出與接受資料的時候，使用vanilla js來做處理。