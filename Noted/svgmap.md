#### SVGMAP [Create Responsive SVG Image Maps](https://www.youtube.com/watch?v=2TM63ing6jY) →   
 - 單獨開啟SVG圖檔
 - 刪除多餘的SVG內容
 - 在每個path用<a xlink:href="網址"></a>包覆
 - 增加CSS樣式來管理SVG
 *將圖片應用至SHAPE裡*
 - 在<a xlink:href="網址"></a>包覆中，增加 <clipPath id="自訂名稱"></clipPath>
 - 在clipPath外 增加 <image xlink:href="圖片路徑與名稱.jpg" clip-path="url(#clipPath的自訂名稱)" x="0" y="0"></image>