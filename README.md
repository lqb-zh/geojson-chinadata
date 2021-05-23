# Geojson-Chinadata

中国各个省份/区级/县级/乡镇 Geojson 数据汇总

## 中国各个省份/区级/县级的 json 数据

数据来源： [datav](http://datav.aliyun.com/tools/atlas/)

缺点：数据来源区级/县级没包含到乡镇数据

## 乡镇数据获取方式

1. [BIGEMAP 全能版本下载](http://download.bigemap.com/bmsetup.rar)

2. 在 BIGEMAP 安装后，右上角选择到乡镇区域，点击导出按钮，保存 kml 文件

3. 进入[geojson.io](http://geojson.io/), 导入 kml 文件自动生成 geojson 数据

4. 当前仓库目录下 china 下的文件就是以上操作生成的，欢迎大家将生成的 geojson 往上传
