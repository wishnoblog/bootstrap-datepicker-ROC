# bootstrap-datepicker-ROC
bootstrap-datepicker 民國年度版本

改寫自 bootstrap-datepicker 1.8 版本，並且已整合zh-TW語系

原始的bootstrap Datepicker在
https://bootstrap-datepicker.readthedocs.io/en/latest/

輸出入格式為
`108-01-01`
，或是
`108-01`

## 線上預覽

![Imgur](https://i.imgur.com/P9aKJHD.png)
![Imgur](https://i.imgur.com/wj4pCFX.png)

https://jsfiddle.net/wishnoblog/hnoLqak0/74/



## 使用方法

HTML

    <div id="banner-message">
      <input type="text" class="datepicker"  value="108-05-10">
    </div>

js

    $('.datepicker').datepicker(
    {
      language: 'zh-TW',
      maxViewModel:1,
      autoclose: true,
    });
    
    
如果你想改成只顯示108-01

    $('.datepicker').datepicker(
    {
      format: 'yyyy-mm',    
      minViewModel:1,
      language: 'zh-TW',
      maxViewModel:1,
      autoclose: true,
    });
    
    
