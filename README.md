# ML100Days

---
### D5：如何新建一個 dataframe? 如何讀取其他資料? (非 csv 的資料)
不同的資料有不同讀取方式
- 文字格式：通常可以用 with open()
- 圖像格式：可以使用 PIL, Skimage 或是 CV2 (CV2 的速度較快，但須注意讀入的格式為 BGR)
- 其他形式如 npy / pickle 可以儲存經過處理後的資料