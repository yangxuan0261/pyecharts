# Version Log

## 版本信息
* version 0.1.4  
    第一个稳定版本

* version 0.1.5  
    新增了 K 线图

* version 0.1.6  
    新增了热力图

* version 0.1.7  
    增加并行显示图表功能

* version 0.1.8  
    * 新增在 Jupyter Notebook 中展示图表功能。感谢 [@ygw365](https://github.com/ygw365) 提供这部分的代码模板 和 [@muxuezi](https://github.com/muxuezi) 协助对代码进行改进!
    * 新增对自定义地图的使用说明  

* version 0.1.9
    * 解决在 macos 下安装出错的问题。感谢 [@chfw](https://github.com/chfw) 提供的解决方案。
    * datazoom 中增加了将组件效果显示在 y 坐标轴中的功能。（参见 KLine 图）
    * 新增对 Pandas 和 Numpy 数据的简单处理。解决直接传入 Pandas 和 Numpy 数据类型出错的问题。（参见开始使用）
    * 新增 Bar3D, Line3D, Scatter3D 三种 3D 立体图表。

* version 0.1.9.1
    * 加入 Travis-CI 自动化测试。感谢 [@chfw](https://github.com/chfw) 提供的代码。  
    * legend 增加 legend_selectedmode 参数，图例可以设置为单例或者多例。（参见 Radar 图）
    * visualmap 组件增加 visual_map 和 visual_range_size 参数。现在支持映射到颜色和图形大小两种方式。（参见 Scatter 图）

* version 0.1.9.2（当前版本）
    * 新增 xaxis_rotate, yaxis_rotate 参数，可通过设置该参数解决强制显示所有坐标轴标签时因过于密集重叠的问题。参见（Bar 图）
    * 新增 xaxis_min, xaxis_max. yaxis_min, yaxis_max 参数，可设置坐标轴上的最大最小值，针对数值轴有效。
    * 解决 3D 图形不能在 jupyter notebook 上正常显示的问题。
    * render() 方法现在为离线模式，实现本地生成 .html 文件，加载速度更快。
    * 废弃 render_notebook() 方法，现可直接调用图形实例显示在 jupyter notebook 上。

## 项目期待

* 更好地集成到 Django + Flask 中。