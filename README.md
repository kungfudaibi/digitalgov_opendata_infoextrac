# .json和.xml信息提取

* 本项目旨在帮助从政府数据开放平台下载的数据进行信息提取(主要包括地标的类型，名称，坐标等)，提取结果为.geojson
* 结果为.json格式的数据[{...}/n....{...}}/n],我使用duqu.py进行修复，之后用json逐行加载
* json中的键和xml中的标签可以自行更改
* 如何使用

  ```
  python xixintiqu your文件夹
  ```