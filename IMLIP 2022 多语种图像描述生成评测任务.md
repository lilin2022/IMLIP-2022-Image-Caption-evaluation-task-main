
# IMLIP 2022 多语种图像描述生成评测任务
为促进多语种智能信息处理研究，加强产学研交流与合作，中国人工智能学会多语种智能信息处理专委会发布“多语种图像描述生成评测任务”

## 1.    任务背景

图像描述生成任务（Image Captioning）旨在生成描述图像的自然语言，该任务涉及到自然语言处理和计算机视觉两个领域多方面的研究问题。近年来受到学术界和工业界的广泛关注，也出现了一些有价值的应用。随着深度学习技术的发展，端到端图像描述生成系统的表现有了大幅度提升。目前图像描述生成任务的公开数据集多为英语和汉语，为了推动多语种图像描述生成研究的发展，我们汇集整理了蒙语、藏语和维语三个语种的图像描述生成数据集，开展本次多语种图像描述生成评测任务，聚焦该任务涉及到的前沿问题，进一步推动多语种智能信息处理研究的发展。

## 2.    任务简介
组织者 

* 赵小兵（中央民族大学）
* 李  琳（青海师范大学）
* 孙  媛（中央民族大学）
* 何中军（百度）
* 周园春（中国科学院计算机网络信息中心）

联系人

* 高歌（中央民族大学）
* 崔璐明（青海师范大学）

评测任务更详细内容可查看评测网站：
https://github.com/Ming-360/IMLIP-2022-Image-Caption-evaluation-task
遇到任何问题请发邮件imlip_2022@163.com或者在Issue中提问，欢迎大家参与。

## 3.    任务简介
图像描述生成任务的目的是为给定图像自动生成高质量的描述文本。本评测任务分为三个子任务，分别为蒙古语、藏语和维吾尔语的图像描述任务。
* 子任务1 蒙语图像描述生成
* 子任务2 藏语图像描述生成
* 子任务2 维语图像描述生成

参赛者可以根据自己的研究兴趣，参与一个或多个子任务。本评测任务要求各位参赛者在现有评测系统基础上针对给定的测试集，研发新的自动评测算法，该评测算法要求在测试集上所得评测结果尽可能地与人工评测结果一致。我们将为参与者提供任务所需数据集和评价方法，并采用客观的评价指标结果作为提交算法的最终成绩。

## 4.    评测数据简介下载

本节介绍各子任务数据集的来源及数据集使用规则、数据集下载链接及评测结果文件的提交格式。本次评测任务所用数据集来自图像描述生成任务的公开数据集Flickr8k，采用机器翻译结合人工校对的方式，我们开发了蒙语、藏语和维吾尔语的Flickr8k数据集。数据集发布后请各位参赛者自行下载并查阅。

### 4.1    蒙语图像描述生成子任务
蒙语图像描述生成数据集样本实例


<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0 width=570
 style='border-collapse:collapse;mso-table-layout-alt:fixed;border:none;
 mso-border-alt:solid windowtext .5pt;mso-yfti-tbllook:1184;mso-padding-alt:
 0cm 5.4pt 0cm 5.4pt'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;page-break-inside:avoid;
  height:1.0cm'>
  <td width=59 style='width:44.3pt;border:solid windowtext 1.0pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>1<o:p></o:p></span></span></p>
  </td>
  <td width=356 style='width:267.25pt;border:solid windowtext 1.0pt;border-left:
  none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black'>&#6184;&#6179;&#6188;&#6176;&#6178;</span></span><span lang=EN-US style='font-size:12.0pt;
  font-family:楷体;mso-bidi-font-family:楷体;color:black'> </span><span
  class=SpellE><span lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";
  mso-fareast-font-family:楷体;color:black'>&#6198;&#6176;&#6189;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'> </span><span
  class=SpellE><span lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";
  mso-fareast-font-family:楷体;color:black'>&#6180;&#6191;&#6176;&#6189;&#6176;&#6184;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'> </span><span
  class=SpellE><span lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";
  mso-fareast-font-family:楷体;color:black'>&#6186;&#6182;&#6190;&#6186;&#6182;&#6189;&#6177;</span></span><span
  lang=EN-US style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;
  color:black'> </span><span class=SpellE><span lang=EN-US style='font-size:
  12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:楷体;color:black'>&#6184;&#6176;&#6189;&#6176;&#6195;&#6196;&#6180;</span></span><span
  lang=EN-US style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;
  color:black'> </span><span class=SpellE><span lang=EN-US style='font-size:
  12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:楷体;color:black'>&#6186;&#6176;&#6178;&#6178;&#6184;&#6158;&#6176;</span></span><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black'>&#6147;<o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>狗<span
  class=GramE>狗</span>正在玩红色的小球<span lang=EN-US><o:p></o:p></span></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:1;page-break-inside:avoid;height:1.0cm'>
  <td width=59 style='width:44.3pt;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>2<o:p></o:p></span></span></p>
  </td>
  <td width=356 style='width:267.25pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6184;&#6179;&#6188;&#6176;&#6178;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'> </span><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6184;&#6176;&#6189;&#6176;&#6195;&#6196;&#6180;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'> </span><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6186;&#6176;&#6178;&#6156;&#6184;&#6158;&#6176;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'> </span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6147;<o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-ascii-font-family:"Mongolian Baiti";mso-hansi-font-family:
  "Mongolian Baiti";mso-bidi-font-family:"Mongolian Baiti";color:black;
  mso-bidi-language:BO'>一个小狗在玩耍</span><span lang=EN-US style='font-size:12.0pt;
  font-family:"Mongolian Baiti";mso-fareast-font-family:楷体;color:black;
  mso-bidi-language:BO'><o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:2;page-break-inside:avoid;height:40.8pt'>
  <td width=59 style='width:44.3pt;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:40.8pt'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>3<o:p></o:p></span></span></p>
  </td>
  <td width=356 style='width:267.25pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:40.8pt'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6184;&#6178;&#6189;&#6177;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'> </span><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6184;&#6179;&#6188;&#6176;&#6178;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'> </span><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6184;&#6176;&#6189;&#6176;&#6195;&#6196;&#6180;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'> </span><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6186;&#6176;&#6198;&#6178;&#6184;&#6158;&#6176;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6147;<o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>一只狗在玩球<span
  lang=EN-US><o:p></o:p></span></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:3;page-break-inside:avoid;height:16.8pt'>
  <td width=59 valign=top style='width:44.3pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:16.8pt'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>4<o:p></o:p></span></span></p>
  </td>
  <td width=356 valign=top style='width:267.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:16.8pt'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6184;&#6178;&#6189;&#6177;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'> </span><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6184;&#6179;&#6188;&#6176;&#6178;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'> </span><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6186;&#6181;&#6190;&#6186;&#6181;&#6189;&#6177;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'> </span><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6184;&#6176;&#6189;&#6176;&#6195;&#6196;&#6180;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'> </span><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6186;&#6176;&#6178;&#6156;&#6184;&#6158;&#6176;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'> </span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6147;<o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>小狗在玩耍<span
  lang=EN-US><o:p></o:p></span></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:4;mso-yfti-lastrow:yes;page-break-inside:avoid;
  height:1.0cm'>
  <td width=59 valign=top style='width:44.3pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>5<o:p></o:p></span></span></p>
  </td>
  <td width=356 valign=top style='width:267.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6184;&#6178;&#6189;&#6177;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'> </span><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6184;&#6179;&#6188;&#6176;&#6178;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'> </span><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6184;&#6176;&#6189;&#6176;&#6195;&#6196;&#6180;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'> </span><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6186;&#6176;&#6198;&#6178;&#6184;&#6158;&#6176;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Mongolian Baiti";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#6147;<o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>一只狗<span
  class=GramE>狗</span>在玩耍<span lang=EN-US><o:p></o:p></span></span></p>
  </td>
 </tr>
</table>





    
### 4.2    藏语图像描述生成子任务
藏语图像描述生成数据集样本实例
<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;mso-table-layout-alt:fixed;border:none;
 mso-border-alt:solid windowtext .5pt;mso-yfti-tbllook:1184;mso-padding-alt:
 0cm 5.4pt 0cm 5.4pt'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;height:1.0cm'>
  <td width=65 style='width:48.5pt;border:solid windowtext 1.0pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>1<o:p></o:p></span></span></p>
  </td>
  <td width=318 style='width:238.5pt;border:solid windowtext 1.0pt;border-left:
  none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Microsoft Himalaya";
  mso-fareast-font-family:楷体;color:black'>&#3905;&#4017;&#3954;&#3851;&#3925;&#4018;&#3956;&#3906;&#3851;&#3906;&#3954;&#3942;&#3851;&#3938;&#4009;&#3962;&#3921;&#3851;&#3928;&#3964;&#3851;&#3938;&#4009;&#3962;&#3851;&#3926;&#3934;&#3954;&#3923;&#3851;&#3936;&#3921;&#3956;&#3906;</span></span><span
  lang=EN-US style='font-size:12.0pt;font-family:"Microsoft Himalaya";
  mso-fareast-font-family:楷体;color:black'><o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>小狗在玩耍。<span
  lang=EN-US><o:p></o:p></span></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:1;height:1.0cm'>
  <td width=65 style='width:48.5pt;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>2<o:p></o:p></span></span></p>
  </td>
  <td width=318 style='width:238.5pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Microsoft Himalaya";
  color:black'>&#3905;&#4017;&#3954;&#3851;&#3934;&#3954;&#3906;&#3851;&#3906;&#3954;&#3942;&#3851;&#3942;&#4004;&#3964;&#3851;&#3939;&#3964;&#3851;&#3938;&#4009;&#3962;&#3921;&#3851;&#3926;&#3934;&#3954;&#3923;&#3851;&#3936;&#3921;&#3956;&#3906;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";color:black'><o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>一只狗在耍球。<span
  lang=EN-US><o:p></o:p></span></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:2;height:1.0cm'>
  <td width=65 style='width:48.5pt;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>3<o:p></o:p></span></span></p>
  </td>
  <td width=318 style='width:238.5pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Microsoft Himalaya";
  color:black'>&#3905;&#4017;&#3954;&#3851;&#3925;&#4018;&#3956;&#3906;&#3851;&#3906;&#3909;&#3954;&#3906;&#3851;&#3906;&#3954;&#3942;&#3851;&#3938;&#4009;&#3962;&#3921;&#3851;&#3928;&#3964;&#3851;&#3938;&#4009;&#3962;&#3851;&#3926;&#3934;&#3954;&#3923;&#3851;&#3936;&#3921;&#3956;&#3906;</span></span><span
  lang=EN-US style='font-size:12.0pt;font-family:"Microsoft Himalaya";
  color:black'><o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>一个小狗在玩耍。<span
  lang=EN-US><o:p></o:p></span></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:3;height:1.0cm'>
  <td width=65 style='width:48.5pt;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>4<o:p></o:p></span></span></p>
  </td>
  <td width=318 style='width:238.5pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Microsoft Himalaya";
  color:black'>&#3905;&#4017;&#3954;&#3851;&#3937;&#3954;&#3942;&#3851;&#3942;&#4004;&#3964;&#3851;&#3939;&#3964;&#3851;&#3921;&#3928;&#3938;&#3851;&#3924;&#3964;&#3851;&#3938;&#4009;&#3962;&#3921;&#3851;&#3926;&#3934;&#3954;&#3923;&#3851;&#3937;&#3964;&#3921;</span></span><span
  lang=EN-US style='font-size:12.0pt;font-family:"Microsoft Himalaya";
  color:black'>&#3853;<o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>狗<span
  class=GramE>狗</span>正在玩红色的小球。<span lang=EN-US><o:p></o:p></span></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:4;mso-yfti-lastrow:yes;height:1.0cm'>
  <td width=65 style='width:48.5pt;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>5<o:p></o:p></span></span></p>
  </td>
  <td width=318 style='width:238.5pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Microsoft Himalaya";
  color:black'>&#3905;&#4017;&#3954;&#3851;&#3934;&#3954;&#3906;&#3851;&#3906;&#3954;&#3942;&#3851;&#3938;&#4009;&#3962;&#3921;&#3851;&#3928;&#3964;&#3851;&#3938;&#4009;&#3962;&#3851;&#3926;&#3934;&#3954;&#3923;&#3851;&#3936;&#3921;&#3956;&#3906;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:"Microsoft Himalaya";color:black'><o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>一只狗<span
  class=GramE>狗</span>在玩耍。<span lang=EN-US><o:p></o:p></span></span></p>
  </td>
 </tr>
</table>


### 4.3    维语图像描述生成子任务
维语图像描述生成数据集样本实例
<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;mso-table-layout-alt:fixed;border:none;
 mso-border-alt:solid windowtext .5pt;mso-yfti-tbllook:1184;mso-padding-alt:
 0cm 5.4pt 0cm 5.4pt'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;height:1.0cm'>
  <td width=65 style='width:48.5pt;border:solid windowtext 1.0pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>1<o:p></o:p></span></span></p>
  </td>
  <td width=318 style='width:238.5pt;border:solid windowtext 1.0pt;border-left:
  none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Courier New";mso-fareast-font-family:
  楷体;color:black'>&#1574;&#1609;&#1578;</span></span><span lang=EN-US style='font-size:12.0pt;
  font-family:楷体;mso-bidi-font-family:楷体;color:black'> </span><span
  class=SpellE><span lang=EN-US style='font-size:12.0pt;font-family:"Courier New";
  mso-fareast-font-family:楷体;color:black'>&#1602;&#1609;&#1586;&#1609;&#1604;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'> </span><span
  class=SpellE><span lang=EN-US style='font-size:12.0pt;font-family:"Courier New";
  mso-fareast-font-family:楷体;color:black'>&#1588;&#1575;&#1585;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'> </span><span
  class=SpellE><span lang=EN-US style='font-size:12.0pt;font-family:"Courier New";
  mso-fareast-font-family:楷体;color:black'>&#1574;&#1608;&#1610;&#1606;&#1609;&#1605;&#1575;&#1602;&#1578;&#1575;</span></span><span
  lang=EN-US style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;
  color:black'>.<o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>狗<span
  class=GramE>狗</span>正在玩红色的小球<span lang=EN-US><o:p></o:p></span></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:1;height:1.0cm'>
  <td width=65 style='width:48.5pt;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>2<o:p></o:p></span></span></p>
  </td>
  <td width=318 style='width:238.5pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Courier New";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#1576;&#1609;&#1585;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black;
  mso-bidi-language:BO'> </span><span class=SpellE><span lang=EN-US
  style='font-size:12.0pt;font-family:"Courier New";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#1574;&#1609;&#1578;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black;
  mso-bidi-language:BO'> </span><span class=SpellE><span lang=EN-US
  style='font-size:12.0pt;font-family:"Courier New";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#1574;&#1608;&#1610;&#1606;&#1609;&#1605;&#1575;&#1602;&#1578;&#1575;</span></span><span
  lang=EN-US style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;
  color:black;mso-bidi-language:BO'>.<o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>一个小狗在玩耍<span
  lang=EN-US><o:p></o:p></span></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:2;height:1.0cm'>
  <td width=65 style='width:48.5pt;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>3<o:p></o:p></span></span></p>
  </td>
  <td width=318 style='width:238.5pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Courier New";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#1576;&#1609;&#1585;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black;
  mso-bidi-language:BO'> </span><span class=SpellE><span lang=EN-US
  style='font-size:12.0pt;font-family:"Courier New";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#1574;&#1609;&#1578;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black;
  mso-bidi-language:BO'> </span><span class=SpellE><span lang=EN-US
  style='font-size:12.0pt;font-family:"Courier New";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#1578;&#1608;&#1662;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black;
  mso-bidi-language:BO'> </span><span class=SpellE><span lang=EN-US
  style='font-size:12.0pt;font-family:"Courier New";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#1574;&#1608;&#1610;&#1606;&#1609;&#1605;&#1575;&#1602;&#1578;&#1575;</span></span><span
  lang=EN-US style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;
  color:black;mso-bidi-language:BO'>.<o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>一只狗在玩球<span
  lang=EN-US><o:p></o:p></span></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:3;height:40.75pt'>
  <td width=65 style='width:48.5pt;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:40.75pt'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>4<o:p></o:p></span></span></p>
  </td>
  <td width=318 style='width:238.5pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:40.75pt'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Courier New";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#1574;&#1609;&#1578;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black;
  mso-bidi-language:BO'> </span><span class=SpellE><span lang=EN-US
  style='font-size:12.0pt;font-family:"Courier New";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#1574;&#1608;&#1610;&#1606;&#1609;&#1605;&#1575;&#1602;&#1578;&#1575;</span></span><span
  lang=EN-US style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;
  color:black;mso-bidi-language:BO'>.<o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>小狗在玩耍<span
  lang=EN-US><o:p></o:p></span></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:4;mso-yfti-lastrow:yes;height:1.0cm'>
  <td width=65 style='width:48.5pt;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=center style='text-align:center'><span
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>参考<span
  lang=EN-US>5<o:p></o:p></span></span></p>
  </td>
  <td width=318 style='width:238.5pt;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:1.0cm'>
  <p class=MsoNormal align=left style='text-align:left'><span class=SpellE><span
  lang=EN-US style='font-size:12.0pt;font-family:"Courier New";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#1576;&#1609;&#1585;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black;
  mso-bidi-language:BO'> </span><span class=SpellE><span lang=EN-US
  style='font-size:12.0pt;font-family:"Courier New";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#1574;&#1609;&#1578;</span></span><span lang=EN-US
  style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black;
  mso-bidi-language:BO'> </span><span class=SpellE><span lang=EN-US
  style='font-size:12.0pt;font-family:"Courier New";mso-fareast-font-family:
  楷体;color:black;mso-bidi-language:BO'>&#1574;&#1608;&#1610;&#1606;&#1609;&#1605;&#1575;&#1602;&#1578;&#1575;</span></span><span
  lang=EN-US style='font-size:12.0pt;font-family:楷体;mso-bidi-font-family:楷体;
  color:black;mso-bidi-language:BO'>.<o:p></o:p></span></p>
  <p class=MsoNormal align=left style='text-align:left'><span style='font-size:
  12.0pt;font-family:楷体;mso-bidi-font-family:楷体;color:black'>一只狗<span
  class=GramE>狗</span>在玩耍<span lang=EN-US><o:p></o:p></span></span></p>
  </td>
 </tr>
</table>

## 5.    结果提交
### 5.1    结果提交格式
  参赛者需提供与给定数据集原始句子索引号相对应的评测结果。方便赛事官方进行结果校验。
提交前，文件需依规范正确命名，并压缩成 .zip 格式文件的压缩包。

提交结果命名：

               track1_test.zip    #压缩包名字

             └── yaclc-csc-test.cvs	# 预测结果文件
             
### 5.2    提交方式
请参赛者将以下材料以邮箱形式进行提交：

    （1）相关技术文档；

    （2）在给定测试集上的评测结果
    
## 6.    评价标准

目前的图像描述生成常用的评测指标包括BLEU、METEOR、ROUGE和CIDEr等。但自动评测方法也存在许多不足之处，如强调生成文本与标准答案之间的 n-gram 重叠，而不考虑生成文本的准确性来评价系统。为了深入理解并解决图像描述生成系统评测问题，先提出本共享任务。

同时为保证参赛者作品的真实性和有效性，我们将通过计算各参赛团队算法提交的自动评测结果和人工评测结果之间的肯德尔等级相关系数（Kendall's tau coefficient）来衡量该算法的好坏，得分高者为优。

## 7.    评测赛程

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0 width="103%"
 style='width:103.54%;margin-left:-5.7pt;border-collapse:collapse;border:none;
 mso-border-alt:solid windowtext .5pt;mso-yfti-tbllook:1184;mso-padding-alt:
 0cm 5.4pt 0cm 5.4pt'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;height:19.85pt'>
  <td width="34%" style='width:34.08%;border:solid windowtext 1.0pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=center style='text-align:center;mso-pagination:widow-orphan'><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>时间</span><span lang=EN-US
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
  <td width="65%" style='width:65.9%;border:solid windowtext 1.0pt;border-left:
  none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=center style='text-align:center;mso-pagination:widow-orphan'><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>事项</span><span lang=EN-US
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:1;height:19.85pt'>
  <td width="34%" style='width:34.08%;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=center style='text-align:center;mso-pagination:widow-orphan'><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-font-kerning:0pt;mso-bidi-language:AR'>11</span><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>月<span lang=EN-US>10</span>日 <span
  lang=EN-US>- 3</span></span><span lang=ZH style='font-size:12.0pt;font-family:
  宋体;mso-bidi-font-family:宋体;color:black;mso-font-kerning:0pt;mso-fareast-language:
  ZH;mso-bidi-language:AR'>月</span><span lang=EN-US style='font-size:12.0pt;
  font-family:宋体;mso-bidi-font-family:宋体;color:black;mso-font-kerning:0pt;
  mso-fareast-language:ZH;mso-bidi-language:AR'>10</span><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>日</span><span lang=EN-US
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black'><o:p></o:p></span></p>
  </td>
  <td width="65%" style='width:65.9%;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=left style='text-align:left;mso-pagination:widow-orphan'><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>报名</span><span lang=ZH
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-fareast-language:ZH;mso-bidi-language:AR'>阶段</span><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>，</span><span lang=ZH
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-fareast-language:ZH;mso-bidi-language:AR'>邮件方式</span><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:2;height:19.85pt'>
  <td width="34%" style='width:34.08%;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=center style='text-align:center;mso-pagination:widow-orphan'><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-font-kerning:0pt;mso-bidi-language:AR'>11</span><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>月<span lang=EN-US>15</span>日</span><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black'><o:p></o:p></span></p>
  </td>
  <td width="65%" style='width:65.9%;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=left style='text-align:left;mso-pagination:widow-orphan'><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>发布所有赛道的训练集和开发集</span><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black'><o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:3;height:19.85pt'>
  <td width="34%" style='width:34.08%;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=center style='text-align:center;mso-pagination:widow-orphan'><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-font-kerning:0pt;mso-bidi-language:AR'>3</span><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>月<span lang=EN-US>10</span>日</span><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
  <td width="65%" style='width:65.9%;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=left style='text-align:left;mso-pagination:widow-orphan'><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>发布测试集</span><span lang=EN-US
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:4;height:19.85pt'>
  <td width="34%" style='width:34.08%;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=center style='text-align:center;mso-pagination:widow-orphan'><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-font-kerning:0pt;mso-bidi-language:AR'>3</span><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>月<span lang=EN-US>20</span>日</span><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
  <td width="65%" style='width:65.9%;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=left style='text-align:left;mso-pagination:widow-orphan'><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>参赛系统结果提交入口开放</span><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:5;height:19.85pt'>
  <td width="34%" style='width:34.08%;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=center style='text-align:center;mso-pagination:widow-orphan'><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-font-kerning:0pt;mso-bidi-language:AR'>4</span><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>月<span lang=EN-US>20</span>日</span><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
  <td width="65%" style='width:65.9%;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=left style='text-align:left;mso-pagination:widow-orphan'><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>参赛系统结果提交入口关闭</span><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:6;height:19.85pt'>
  <td width="34%" style='width:34.08%;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=center style='text-align:center;mso-pagination:widow-orphan'><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-font-kerning:0pt;mso-bidi-language:AR'>4</span><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>月<span lang=EN-US>30</span>日</span><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
  <td width="65%" style='width:65.9%;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=left style='text-align:left;mso-pagination:widow-orphan'><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>截止提交评测任务技术报告</span><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:7;height:19.85pt'>
  <td width="34%" style='width:34.08%;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=center style='text-align:center;mso-pagination:widow-orphan'><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-font-kerning:0pt;mso-bidi-language:AR'>5</span><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>月<span lang=EN-US>30</span>日</span><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
  <td width="65%" style='width:65.9%;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=left style='text-align:left;mso-pagination:widow-orphan'><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>公布评测结果</span><span lang=EN-US
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:8;mso-yfti-lastrow:yes;height:19.85pt'>
  <td width="34%" style='width:34.08%;border:solid windowtext 1.0pt;border-top:
  none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=center style='text-align:center;mso-pagination:widow-orphan'><span
  lang=EN-US style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;
  color:black;mso-font-kerning:0pt;mso-bidi-language:AR'>6</span><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>月</span><span lang=EN-US
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
  <td width="65%" style='width:65.9%;border-top:none;border-left:none;
  border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:19.85pt'>
  <p class=MsoNormal align=left style='text-align:left;mso-pagination:widow-orphan'><span
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-font-kerning:0pt;mso-bidi-language:AR'>评测研讨会</span><span lang=EN-US
  style='font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体;color:black;
  mso-fareast-language:ZH'><o:p></o:p></span></p>
  </td>
 </tr>
</table>


## 8.    报名方式
以机构、团体或个人名义均可报名参加，有意向的参赛者可通过发送邮件的方式进行报名，地址为imlip_2022@163.com，参赛者应提供队名、单位、联系方式等个人信息，方便与各位参赛者取得联系。

## 参考文献
1.    Li X, Lan W, Dong J, et al. Adding chinese captions to images[C]//Proceedings of the 2016 ACM on international conference on multimedia retrieval. 2016: 271-275.
2.	Papineni K, Roukos S, Ward T, et al. Bleu: a method for automatic evaluation of machine translation[C]//Proceedings of the 40th annual meeting of the Association for Computational Linguistics. 2002: 311-318.
3.	Lin C Y. Rouge: A package for automatic evaluation of summaries[C]//Text summarization branches out. 2004: 74-81.
4.	Banerjee S, Lavie A. METEOR: An automatic metric for MT evaluation with improved correlation with human judgments[C]//Proceedings of the acl workshop on intrinsic and extrinsic evaluation measures for machine translation and/or summarization. 2005: 65-72.
5.	Vedantam R, Lawrence Zitnick C, Parikh D. Cider: Consensus-based image description evaluation[C]//Proceedings of the IEEE conference on computer vision and pattern recognition. 2015: 4566-4575.
6.	Vinyals O, Toshev A, Bengio S, et al. Show and tell: A neural image caption generator[C]//Proceedings of the IEEE conference on computer vision and pattern recognition. 2015: 3156-3164.




