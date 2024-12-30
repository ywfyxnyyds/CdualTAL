Tool Wear Prediction —— CdualTAL

CdualTAL: A Research on Tool Wear Prediction Based on Multi-domain Principal Feature Enhancement

# Data
The PHM 2010 dataset consists of six parts, where C1, C4, and C6 are the tool wear datasets for three different tools with labeled data, and C2, C3, and C5 are the datasets for the same three tools without labels. 
This research selects the labeled C1, C4, and C6 datasets as experimental data. Each dataset has a dimension of 315×7, containing milling force signals in the Z, Y, and X directions, vibration signals, and acoustic emission signals collected from 315 tool passes. Download the dataset at https://www.kaggle.com/datasets/rabahba/phm-data-challenge-2010

The experimental environment is shown below：
![Experimental Conditions](https://github.com/user-attachments/assets/794f785d-218d-470b-89b8-199615f39a20)

Considering the zero drift phenomenon in the C1, C4, and C6 datasets, the tool exhibits continuous wear during actual use. Therefore, the X, Y, and Z sensor signals from all three datasets were preprocessed to mitigate the effects of this issue. Twenty-four time-domain, frequency-domain, and time-frequency-domain features were extracted from the original signal samples of C1, C4, and C6.The cross-validation method iterates through alternating training and validation sets. 
# CdualTAL document
The files, **CdualTAL-C1.ipynb**, **CdualTAL-C4.ipynb** and **CdualTAL-C6.ipynb** document the experimental procedure and experimental results of the CdualTAL model on the C1, C4, and C6 tool wear data sets.
**Data process.ipynb** documents the data feature extraction process and visualisation.

二、编辑基本语法  
1、字体格式强调
 我们可以使用下面的方式给我们的文本添加强调的效果
*强调*  (示例：斜体)  
 _强调_  (示例：斜体)  
**加重强调**  (示例：粗体)  
 __加重强调__ (示例：粗体)  
***特别强调*** (示例：粗斜体)  
___特别强调___  (示例：粗斜体)  
2、代码  
`<hello world>`  
3、代码块高亮  
```
@Override
protected void onDestroy() {
    EventBus.getDefault().unregister(this);
    super.onDestroy();
}
```
4、表格 （建议在表格前空一行，否则可能影响表格无法显示）
 
 表头  | 表头  | 表头
 ---- | ----- | ------  
 单元格内容  | 单元格内容 | 单元格内容 
 单元格内容  | 单元格内容 | 单元格内容  
 
5、其他引用
图片  
![图片名称](https://i-blog.csdnimg.cn/img_convert/fbcbccbbb91a2255bab8c9f53fea1cfd.png)  
链接  
[链接名称](https://www.baidu.com/)    
6、列表 
1. 项目1  
2. 项目2  
3. 项目3  
   * 项目1 （一个*号会显示为一个黑点，注意⚠️有空格，否则直接显示为*项目1） 
   * 项目2   
 
7、换行（建议直接在前一行后面补两个空格）
直接回车不能换行，  
可以在上一行文本后面补两个空格，  
这样下一行的文本就换行了。
或者就是在两行文本直接加一个空行。
也能实现换行效果，不过这个行间距有点大。  
 
8、引用
> 第一行引用文字  
> 第二行引用文字   
