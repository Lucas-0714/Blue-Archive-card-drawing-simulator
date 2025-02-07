# 蔚藍檔案抽卡模擬器
  本模擬器由@Lucas-0714以Python(JupyterNotebook)編寫而成，故可以於Google Colab中開啟（詳見[開啟方式](https://github.com/Lucas-0714/Blue-Archive-card-drawing-simulator/blob/main/README.md#開啟方式)）

# 代碼分析
  ```
  def displayimage(link, delay):
    # exchange by display(Image(url=link))
    display(HTML(f'<img src="{link}" alt="animation" width="300px">'))
    time.sleep(delay)
  ```
  定義displayimage(link, delay)函式，並要求輸入連結與延遲，透過HTML

# 開啟方式
  透過Google Colab開啟：<br>
  連結：[colab.resaerch.google.com](https://colab.research.google.com/github/Lucas-0714/Blue-Archive-card-drawing-simulator/blob/main/Blue_Archive.ipynb)
  
  透過檔案中Colab標誌連結
  
