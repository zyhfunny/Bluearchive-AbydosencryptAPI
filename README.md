# ABYDOSCODEAPI

***聞喘ba嶄唖維謹帽斤貨溜埀氏撹埀議兆各栖紗畜忖憲堪***

---

## 1. API萩箔鯉塀

### 1.1 紗畜

**GET:**

```
GET /code?input=<your_input>&key=<your_key> HTTP/1.1
Host: <your_ip>:5000
```

**POST:**

```
POST /code HTTP/1.1
Host: <your_ip>:5000
Content-Type: application/json

{
    "Input": "<your_input>",
    "Key": <your_key>
}
```

### 1.2 盾畜

**GET:**

```
GET /decode?input=<your_input>&key=<your_key> HTTP/1.1
Host: <your_ip>:5000
```

**POST:**

```
POST /decode HTTP/1.1
Host: <your_ip>:5000
Content-Type: application/json

{
    "Input": "<your_input>",
    "Key": <your_key>
}
```
**廣吭�再籌�<your_ip>頁低何俸api議捲暦匂議ip仇峽(云仇ip:127.0.0.1)、<your_input>頁低�誨�荷恬議忖憲堪、<your_key>頁低柴麻竃議key(秀咏俐個柴麻圭塀)**<br>
**潮範key柴麻圭塀��**

**Python**

```python
from datetime import datetime
math.floor(int((datetime.now() - datetime(1970, 1, 1)).total_seconds())+math.sqrt(int((datetime.now() - datetime(1970, 1, 1)).total_seconds())))
```

**C#**

```csharp
Math.Floor(((int)(DateTime.Now.Subtract(new DateTime(1970, 1, 1))).TotalSeconds) + Math.Sqrt(((int)(DateTime.Now.Subtract(new DateTime(1970, 1, 1))).TotalSeconds)))
```

---
## 2. api�贄Ω駟�
```json
{
    "result":"<string>"
}
```
### 幣箭(紗畜)��<br>
**萩箔(GET)��**<br>
```
http://localhost:5000/code?input=test&key=<your_key>
```
**�贄Γ�**
```json
{
    "result":"きいつシロコとにつノノミとユろいつシロコといつホシノとユきいつシロコといつノノミとユきいつシロコとにつノノミとユ"
}
```
---
## 3. 處幣嫋泣

**珊短秀挫qwq**

---

## 4. 硫蕗

**宸峪頁匯倖*兜嶄伏*涙祖壗竃栖議~~樋崘~~螺吭��泌惚嗤音怎賜危列辛參峺竃��徽音勣卓厘**<br>
**湖仍[@hcymc](https://github.com/hcymc)戻工議念極旗鷹屶隔(埋隼珊短貧勧)**
