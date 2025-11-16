---

# **📌 BiGNAS-Attack 結果總覽（Offset 後 ID 版本）**

---

## **🧩 Dataset Statistics**

**（User、Source Domain Item、Target Domain Item 都已做 offset 處理）**

| Domain     | Item 數量 | Record 數量 | Sparsity  |
| ---------- | ------- | --------- | --------- |
| **Source** | 28,253  | 53,995    | 0.070210% |
| **Target** | 14,274  | 37,559    | 0.093673% |

---

## **❄️ Cold Item Debug**

`cold_item_id = 31334`

| Split     | 次數 |
| --------- | -- |
| **Train** | 10 |
| **Valid** | 0  |
| **Test**  | 0  |

---

## **🎯 Target Domain Split Size**

| Split     | Size   |
| --------- | ------ |
| **Train** | 31,941 |
| **Valid** | 2,809  |
| **Test**  | 2,809  |

---

# **📊 Evaluation Metrics (@K)**

以下結果計算於 **2,809 位 target domain users**。

---

## **🎯 HIT RATIO 與 ER（Exposure Rate）**

### **@10**

* **Hit Ratio@10:** 0.1570
* **ER@10:** 0.0000
  （Cold Item Hits = 0）

---

### **@15**

* **Hit Ratio@15:** 0.1994
* **ER@15:** 0.0000
  （Cold Item Hits = 0）

---

### **@20**

* **Hit Ratio@20:** 0.2350
* **ER@20:** 0.0235
  （Cold Item Hits = 66）

---

### **@25**

* **Hit Ratio@25:** 0.2681
* **ER@25:** 0.1883
  （Cold Item Hits = 529）

---

### **@30**

* **Hit Ratio@30:** 0.3008
* **ER@30:** 0.5910
  （Cold Item Hits = 1660）

---


✨ 幫你加圖表
✨ 幫你加顏色強調
✨ 幫你產生對比版本（有 Hard User / 無 Hard User）
✨ 加入摘要版 for 報告

只要告訴我要不要更漂亮！
