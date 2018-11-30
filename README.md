# AVBookCode

### 源码

链接:https://pan.baidu.com/s/1_ZKhaIKahuiUXCJRPGiEhQ  密码:zc8b

### 码流分析工具

链接：https://pan.baidu.com/s/1iUksNQ8MW3JHw258cb3Yzw  密码：e08o 

### 勘误列表

- 1、Page-3，Line-8，错误类型--错别字，AudioTrack 写成 "AudiTrack";
- 2、Page-6，错误类型--描述错误，关于PCM的采样率和比特率换算，常见的比特率并没有44.1Hz，而是44.1KHz，即使是44.1Hz，16位的精度，换算的比特率也不是4410016kb/s的结果;
- 3、第一章中关于YUV的概念介绍中说 :“YUV：也被称作YCrCb”, 应为“YCbCr”, 在YUV家族中，YCbCr是在计算机系统中应用最多的成员，其应用领域很广泛，JPEG、MPEG均采用此格式。一般人们所讲的YUV大多是指YCbCr。引用微软对YV12和NV12的描述：https://docs.microsoft.com/en-us/previous-versions/aa904813(v=vs.80)

YV12
　　All of the Y samples appear first in memory as an array of unsigned char values. This array is followed immediately by all of the V (Cr) samples. The stride of the V plane is half the stride of the Y plane, and the V plane contains half as many lines as the Y plane. The V plane is followed immediately by all of the U (Cb) samples, with the same stride and number of lines as the V plane (Figure 12).

NV12
　　All of the Y samples are found first in memory as an array of unsigned char values with an even number of lines. The Y plane is followed immediately by an array of unsigned char values that contains packed U (Cb) and V (Cr) samples, as shown in Figure 13. When the combined U-V array is addressed as an array of little-endian WORD values, the LSBs contain the U values, and the MSBs contain the V values. NV12 is the preferred 4:2:0 pixel format for DirectX VA. It is expected to be an intermediate-term requirement for DirectX VA accelerators supporting 4:2:0 video.

可以发现 U (Cb) ，V (Cr)，那YUV就是YCbCr.

- 4、Page-23处libmedia.so库源文件的目录不是frameworks/base/media/libmedia，而是在frameworks/av/media/libmedia
- 5、Page-15，得到软引用对象，应为“得到弱引用对象”
- 6、Page-210 metadata，应为“元数据”
- 7、Page-212 priv_data_size，应为“某种格式文件的数据大小”

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
