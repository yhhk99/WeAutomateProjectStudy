# WeAutomateProjectStudy
***
Huawei RAP WeAutomate base project Study
本项目是使用Huawei RPA WeAutomate进行编写，项目建立之初版本号为2.1.18，引中途个人原因，导致2.1.18版本丢失，无奈使用3.0.0版本RPA进行项目重新调试，且完全调试通过后进行上传仓库。

## 目录


* ### stu_demo
* #### stu_1_demo
    第一个RPA项目，输出hello word

* #### stu_2_demo
    第二个RPA项目，用于展示RPA部分控件使用，实现了打开百度网页，搜索"论十大关系 知乎”功能，对检索结果进行查看，关闭知乎登录弹窗，复制搜索结果并保存到output文件下的 webTextOutput.xlsx文功能

- ###  ep_demo


#### ep_4_3_7_demo
    使用组件："eval 运用python表达式"，判断array中最大的数值

#### ep_4_3_6_demo
    使用组件："eval 运用python表达式", 拼接多个字符串

#### ep_4_4_1_demo
    使用组件："eval 运行python表达式"，将字符串中大写字母转化为小写字母

#### ep_4_4_4_demo
   使用组件："string.contain-包含子串" 检查待处理字符串中是否包含子串，如果包含，输出contain，否则输出NotContain

#### ep_4_4_6_demo
    使用组件："string.split - 分割字符串",实现string类型的全局变量按要求分割


#### ep_4_4_7_demo
    使用组件："eval 运用python表达式"，实现string类型中字符替换，类似python str.replace("A","B")

#### ep_4_4_8_demo
    使用组件："eval 运用python表达式"，实现将string类型的值拼接到给其他变量 python str.join()

#### ep_4_4_10_demo
    使用组件："eval 运用python表达式"，实现去除String类型值前的空格，python str.strip()

#### ep_4_4_12_demo
    使用组件："eval 运用python表达式"，实现在Array类型的全局变量后添加值，python list.append()

#### ep_4_4_16_demo
    使用组件："流程控制 For",实现循环输出全局变量中Array类型中的值

#### ep_4_4_17_demo

#### ep_4_4_18_demo


#### ep_4_4_20_demo
    使用组件："eval 运用python表达式"，实现更新全局变量Arrayt类型中的值
#### ep_4_4_21_demo
    使用组件："eval 运用python表达式"，实现更新全局变量Object类型中的值

#### ep_4_4_22_demo
    使用组件："eval 运用python表达式"，实现删除全局变量Object类型中特定的值

#### ep_4_4_23_demo
    使用组件："getObjectValuee-字典取值"，实现获取全局变量Object类型中特定值
    
#### ep_4_4_24_demo
    使用组件："getCurrentTime-获取时间"，实现输出当前日期和时间功能

#### ep_4_4_25_demo
    使用组件："eval 运用python表达式"，调用datetime包，实现输出指定日期和时间功能

#### ep_4_4_27_demo
    使用组件："eval 运用python表达式"，调用datetime包，实现输出当前日期和时间

    ep_4_4_24_demo 和ep_4_4_27的区别在于：
        前者输出为：xxxx年xx月xx日 xx:xx:xx
        后者输出为：xxxx-xx-xx xx:xx:xx

#### ep_4_4_28_demo
    使用组件："eval 运用python表达式"，调用datetime包，实现分别输出当前年月日

#### ep_4_4_30_demo
    使用组件："eval 运用python表达式"，调用re包中的match()方法，实现对字符串进行截取

#### ep_4_5_1_demo
    使用组件："流程控制 if", 实现判断输出，相当于 python中 if i <= 18: statement_A else: statement_B

#### ep_4_5_2_demo
    使用组件："流程控制 while" "eval-运行python表达式", 实现了循环输出，相当于 python中 for i in range(xx); c++中 for (i=0; i<x; i++)

#### ep_4_5_3_demo
#### ep_4_5_4_demo
    使用组件："流程控制 For",实现依次循环输出Array类型的全局变量

    ep_4_4_16 与 ep_4_5_5_demo 的区别：
        两者功能相同，后者比前者多了一个退出输出内容

#### ep_4_6_1_demo


#### ep_4_6_3_demo
    使用组件："openurl-打开网页""click-鼠标单击网页元素"，实现打开华为官网功能

    
