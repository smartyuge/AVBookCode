# AVBookCode

### 源码

链接:https://pan.baidu.com/s/1_ZKhaIKahuiUXCJRPGiEhQ  密码:zc8b

### 勘误列表

- 1、Page-3，Line-8，错误类型--错别字，AudioTrack 写成 "AudiTrack";
- 2、Page-6，错误类型--描述错误，关于PCM的采样率和比特率换算，常见的比特率并没有44.1Hz，而是44.1KHz，即使是44.1Hz，16位的精度，换算的比特率也不是4410016kb/s的结果;
- 3、第一章中关于YUV的概念介绍中说 :“YUV：也被称作 YCrCb”
这里，应该是YCbCr，而不是YCrCb，而且YUV和 YCbCr是两个不同的概念。引用自维基百科的解释
YUV是编译true-color颜色空间（color space）的种类，Y'UV, YUV, YCbCr，YPbPr等专有名词都可以称为YUV，彼此有重叠。“Y”表示明亮度（Luminance、Luma），“U”和“V”则是色度、浓度（Chrominance、Chroma）
- 4、Page-23处libmedia.so库源文件的目录不是frameworks/base/media/libmedia，而是在frameworks/av/media/libmedia

License
--------
```
    Copyright (C) <2018>  <hejunlin>

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
