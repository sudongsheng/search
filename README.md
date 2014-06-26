# 南京邮电大学补考查询

数据源来自教务处网站，用Office将教务处的Excel表格转成CSV文件，用`csv2json.rb`这个Ruby脚本将其转换成JSON数据。

前端采用AngularJS，一次将JSON全部读取，然后根据搜搜索框的学号查询实时展现数据。

文件结构
       
    ├── README.md
    ├── about.html    
    ├── favicon.ico
    ├── index.html     
    └── static
        ├── app.css
        ├── app.js     
        ├── bukao2013.csv
        ├── bukao2013.json
        └── csv2json.rb