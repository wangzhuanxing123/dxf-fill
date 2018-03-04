# dxf-fill
可进行dxf图形的自动填充，采用LabVIEW编写（Dxf graphics can be automatically filled, written in LabVIEW）

使用方法：（1）本程序在LabVIEW 2014中编写，需要安装NI Vision（2）先打开dxf路径
               （3）运行之后显示出dxf图形，在“DXF图”界面鼠标点击需要填充的地方即可实现自动填充
注意：dxf图中仅支持“线段”、“圆”、“圆弧”，矩形或多边形需要分解爆炸成线段后保存DXF，不支持椭圆及椭圆弧

Usage: (1) The program written in LabVIEW 2014, you need to install NI Vision (2) First open the dxf path
           (3) after the operation shows dxf graphics, in the "DXF" interface, the mouse click where you need to fill can
                be automatically filled
Note: DXF only supports "segment", "circle", "arc", rectangle or polygon needs to be decomposed into DXF, DXF is 
          saved, ellipse and elliptical arc are not supported
