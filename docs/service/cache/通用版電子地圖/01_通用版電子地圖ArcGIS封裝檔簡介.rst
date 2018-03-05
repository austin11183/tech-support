通用版電子地圖ArcGIS封裝檔簡介
==============================

通用版電子地圖ArcGIS封裝檔是國土測繪中心製作公開的資料，允許使用者在電腦、行動裝置上離線瀏覽地圖。下載來的檔案解壓縮後，目錄結構會類似下圖，此為ArcGIS
Cache Service的檔案結構。

    |image0|

由於國土測繪沒有附上Cache
Service的圖磚定義檔案(Conf.xml與conf.cdi)，所以使用者需要自己建立或，或是直接\ `下載已經建立好的定義檔 <https://drive.google.com/drive/folders/1BiopRK44EYJUWZTo1gX_88_2-hAQSbix?usp=sharing>`__\ ，才能在ArcMap或是對應軟體中開啟地圖資料。

以下小節會介紹如何自己建立圖磚定義檔案，並說明建立圖磚定義檔時，需要注意那些細節。

.. |image0| image:: ./01_通用版電子地圖ArcGIS封裝檔簡介/image1.png
   :width: 6.60417in
   :height: 2.57771in
