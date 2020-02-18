# china-area-json
全国省市区的JSON信息，带区域CODE，并修复部分城市和下属区县CODE冲突问题

格式如下，适合做省市区联动&树形菜等
````json
[
    {
        "provinceCode": "110000",
        "provinceName": "北京市",
        "mallCityList": [
            {
                "cityCode": "110100",
                "cityName": "北京市",
                "mallAreaList": [
                    {
                        "areaCode": "110101",
                        "areaName": "东城区"
                    },
                    {
                        "areaCode": "110102",
                        "areaName": "西城区"
                    },
                    {
                        "areaCode": "110105",
                        "areaName": "朝阳区"
                    }]
                    }]
                    }]
````
