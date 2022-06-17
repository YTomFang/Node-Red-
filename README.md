Node-Red
===
## 組員
B0942046 方禹棠
B0742306 陳道昇

## 目錄

* [Node-red 介紹](https://github.com/YTomFang/Node-Red-/edit/main/README.md#node-red-%E4%BB%8B%E7%B4%B9)
* [Node-red 安裝步驟](https://github.com/YTomFang/Node-Red-/edit/main/README.md#node-red-%E5%AE%89%E8%A3%9D%E6%AD%A5%E9%A9%9F)
* [Dashboard 應用](https://github.com/YTomFang/Node-Red-/edit/main/README.md#%E6%87%89%E7%94%A8)

## Node-red 介紹
Node-Red是一個使用瀏覽器介面的強大物聯網 (IoT) 開發工具，其視覺開發環境以流程 (flows) 為基礎，使應用程式撰寫更加簡易。其程式語言涵蓋範圍相當廣，包含了多種的程式設計風格以及範例。其中以指令式以及物件導向程式設計主宰這個領域，但也有為生產軟體以及快速將點子原型化的替代選擇。Node-RED 採取另一種方式來開發軟體。Node-RED 相對來說是較年輕的環境，源於 IBM ，隨後於 2013 年被釋放為 open source 。這個工具當初被設計為物聯網程式設計工具，但由於他的簡便以及廣泛的可用性而使其成長。
![image](https://user-images.githubusercontent.com/106374301/172999059-69877207-ff40-4165-82c6-fb809eb23555.png)

節點與節點種類:
Node-RED 包含了相當豐富的節點，會讓您馬上具備生產力。擁有輸入以及輸出節點，其允許 MQTT 訂閱與接收主題 (topics) 、輸出 MQTT 主題至中介器 (broker) 、透過 HTTP requests（以及建構 HTTP response）設計網路服務，以及可以創建伺服器的低階 TCP 、 UDP 服務，接收輸入以及產生輸出。
![image](https://user-images.githubusercontent.com/106374301/172999569-fc34e37c-e9da-4be7-93b7-ff9c74d32601.png)
## Node-red 安裝步驟
1.首先我們需要先到node.js官網下載最新版本的node.js安裝套件
![image](https://user-images.githubusercontent.com/106374301/172999863-8eaa8c65-98ed-43c8-8b3a-eac16f0b1866.png)
 輸入指令: sudo apt install node js 
 ![image](https://user-images.githubusercontent.com/106374301/174231937-80346e75-1ff9-421b-b100-adff0f1f8981.png)

2.輸入指令 sudo apt install npm
![image](https://user-images.githubusercontent.com/106374301/173000035-6a2b1741-51a1-4b63-bb87-afffe105f34a.png)

3.輸入指令sudo npm install -g --unsafe-perm node-red
![image](https://user-images.githubusercontent.com/106374301/173000244-94c6e5ab-3ce7-4760-ae88-78bba2eea7d6.png)

4.輸入node-red
![image](https://user-images.githubusercontent.com/106374301/173000316-59e94571-0427-4093-b3d0-dfe90767d918.png)

5.啟動瀏覽器 輸入127.0.0.1:1880
![image](https://user-images.githubusercontent.com/106374301/173000391-db4a410b-dcc8-4fa0-b89b-52e5d413a7ae.png)

## 應用

1.拉3個方塊

![image](https://user-images.githubusercontent.com/106374301/174235022-a7317fb2-aa01-46d9-831d-d1fb2451d83e.png)

2.選擇http方塊 輸入tes1
![image](https://user-images.githubusercontent.com/106374301/174234257-f6dc68fb-625e-424a-b954-f77136661f3b.png)
3.選擇橘色方塊輸入程式碼
![image](https://user-images.githubusercontent.com/106374301/174234302-95b6aaab-e4f7-4a44-a699-797e3b25a426.png)
4.輸入網址

![image](https://user-images.githubusercontent.com/106374301/174234344-993776b1-3c5f-43dd-8723-09ae26d1b2e5.png)

5.帶入頁面並顯示程式碼中的Hellow world
![image](https://user-images.githubusercontent.com/106374301/174234361-15cd65dc-d468-48c4-a09c-6f4904b3db6c.png)
6.拉3個方塊
![image](https://user-images.githubusercontent.com/106374301/174234396-3cf61b96-373e-4580-9596-eddb1b0e4879.png)
7.選取button方塊 在payload輸入 Hellow Word
![image](https://user-images.githubusercontent.com/106374301/174234414-07b57f25-b866-4784-9a0e-1010d5845912.png)
8.創立一個新的group
![image](https://user-images.githubusercontent.com/106374301/174234431-76c767a1-c48d-4b2a-afc4-cd2e73dd76e2.png)
9.選取text方塊 加入新的group
![image](https://user-images.githubusercontent.com/106374301/174234462-3c351159-04b7-4047-acaf-496ec2259db3.png)
10.輸入網址

![image](https://user-images.githubusercontent.com/106374301/174234475-803ee4d4-6ede-4aab-b7ad-a1ed0bf20ae7.png)

11.按下BUTTON即可顯示Hellow Word
![image](https://user-images.githubusercontent.com/106374301/174234484-89c98e51-fe73-4cdf-8eb2-9271b251685a.png)

















