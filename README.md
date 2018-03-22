# 2018_pingan_behavior_predicting_driving_risk
2018平安产险数据建模大赛 驾驶行为预测驾驶风险
作品要求:
http://www.datafountain.cn/#/competitions/284/requirements
      【 提交内容 】
      程序启动主入口
           程序的主入口文件为main.py，请确定建模程序可以通过python main.py启动。
      日志输出规范
           日志统一使用print()输出日志。
           日志大小应小于1Mb
           注：不使用print输出时，平台不会返回相关日志信息。
    
      建模程序需要指定结果的输出目录，把结果文件输出到主目录下的model文件下。如model/xx.csv,有且只能有一个文件并且是CSV格式。   
图片2
      注：必须输出结果文件，没有结果输出就没有得分。

      输出csv文件格式：

微信图片_20180306181922

      注：只有两列，一列Id为用户Id，一列Pred为预测结果(请注意大小写)。
      CSV文件大小应小于5Mb，且行数必须跟评测集行数一致（test中为客户分钟级数据，输出预测值时请注意去重）

python版本说明
python版本为：Python 3.6.1
支持包列表：
absl-py (0.1.11)
astor (0.6.2)
bleach (1.5.0)
cycler (0.10.0)
gast (0.2.0)
geojson (2.3.0)
geopy (1.11.0)
gps3 (0.33.3)
grpcio (1.10.0)
html5lib (0.9999999)
Keras (2.1.5)
kiwisolver (1.0.1)
Markdown (2.6.11)
matplotlib (2.2.0)
numpy (1.14.1)
pandas (0.22.0)
Pillow (5.0.0)
pip (9.0.1)
protobuf (3.5.2)
pyparsing (2.2.0)
python-dateutil (2.6.1)
pytz (2018.3)
PyYAML (3.12)
scikit-learn (0.19.1)
scipy (1.0.0)
setuptools (28.8.0)
six (1.11.0)
tensorboard (1.6.0)
tensorflow (1.3.0rc1)
tensorflow-tensorboard (1.5.1)
termcolor (1.1.0)
tflearn (0.3.2)
Theano (1.0.1)
Werkzeug (0.14.1)
wheel (0.30.0)
xgboost (0.7.post3)
 
【 提交格式 】
      打包规范如下：需要对建模程序进行打包。
      在程序主目录外面打包，并且需打成zip格式文件，zip内有且只能有一个文件夹，如: df_test0209_01, 否则会返回错误
 
      如下图所示：
     图片6
      其中df_test0209_01下为建模程序，18020900001.zip为打包好的待提交的建模程序文件。
 
      18020900001.zip的目录层级为：
 图片7

图片8

【 提交样例 】
      报名比赛后可在本竞赛页面看到“数据下载”窗口，未报名为不可见状态

