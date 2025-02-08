# 蔚藍檔案抽卡模擬器
  本模擬器由@Lucas-0714以Python(JupyterNotebook)編寫而成，故可以於Google Colab中開啟（詳見[開啟方式](https://github.com/Lucas-0714/Blue-Archive-card-drawing-simulator/blob/main/README.md#開啟方式)）

# 代碼分析
  ```
  def displayimage(link, delay):
    # exchange by display(Image(url=link))
    display(HTML(f'<img src="{link}" alt="animation" width="300px">'))
    time.sleep(delay)
  ```
  定義displayimage(link, delay)函式，並要求輸入連結與延遲，透過HTML[^1]文本簡易的輸出圖片，再透過time[^2]模組執行{delay}秒的延遲。

  ```
  def run():
    displayimage("https://i.imgur.com/Y2aak8Y.jpeg", 0.3)
    clear_output()
    displayimage("https://i.imgur.com/BPLJ8fD.jpeg", 0.3)
    clear_output()
    ...
  ```
  定義run()函式，函式的內容在於顯示一連串的照片（類似逐格動畫），先顯示一張照片，然後用clear_output[^3]模組清除輸出，進而達到

  [^1]: ```
        from IPython.display import HTML, display
  [^2]: ```
        import time
  [^3]: ```
        from IPython.display import clear_output
# 開啟方式
  透過Google Colab開啟：<br>
  連結：[colab.resaerch.google.com](https://colab.research.google.com/github/Lucas-0714/Blue-Archive-card-drawing-simulator/blob/main/Blue_Archive.ipynb)
  
  透過檔案中Colab標誌連結
  
