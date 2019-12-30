# IPsec
https://zh.wikipedia.org/wiki/IPsec

網際網路安全協定（***I***nternet ***P***rotocol ***Sec***urity）:
是一個協定套件，透過對IP協定的封包進行加密和認證來保護IP協定的網路傳輸協定族（一些相互關聯的協定的集合）。

In computing, 
Internet Protocol Security (IPsec) is a secure network protocol suite that authenticates and encrypts the packets of data sent over 
an Internet Protocol network. It is used in virtual private networks (VPNs).

IPsec主要由以下協定組成：  
1.**認證頭（AH）**:為IP資料報提供無連接資料**完整性**、訊息認證以及防重放攻擊保護  
2.**封裝安全載荷（ESP）**:提供**機密性**、資料來源認證、無連接完整性、防重放和有限的傳輸流（traffic-flow）機密性  
3.**安全關聯（SA）**:提供演算法和封包，提供AH、ESP操作所需的參數  
### 認證頭(AH)
```
認證頭（Authentication Header，AH）被用來保證被傳輸封包的完整性和可靠性。
此外，它還保護不受重放攻擊。認證頭試圖保護IP資料報的所有欄位，那些在傳輸IP封包的過程中要發生變化的欄位就只能被排除在外。
當認證頭使用非對稱數位簽章演算法（如RSA）時，可以提供不可否認性
```
### 封裝安全載荷（ESP）
```
封裝安全載荷（Encapsulating Security Payload，ESP）協定對封包提供了源可靠性、完整性和保密性的支援。
與AH頭不同的是，IP封包頭部不被包括在內。
```
