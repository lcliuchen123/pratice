# 2018年12月-2019年8月实习总结
## 一、实习经历1
    实习地点：北京牡丹园
    实习公司：字节跳动旗下的今日头条
    实习时间：2018年11月-2019年1月
    实习内容：
        1. 退款分析维度：各个城市的退款金额，已消耗金额，退款率，退款周期，退款原因。
        2. 参与设计问卷，进行全量回访，了解客户的真实退款原因。
        3. 首先选取的聚类指标：用户所在地区，行业类别，充值时间，已消耗金额，充值金额，充值时长，上线时间。
           利用K均值聚类将退款用户分为5类，然后选取退款金额和上线时间进行加权求和，对每类退款客户进行定级。
           计算未退款用户跟每个用户之间的距离，选择距离近的交给退款挽回系统。
## 二、实习经历2（只待了一天）
2019年2月13日--2019年2月14日 神州医疗 医学图像处理
## 三、实习经历3
    实习地点：上海崂山路
    实习公司：平安科技（深圳）有限公司上海分部
    实习时间：2019年2月-2019年6月
    实习内容：
        1. 清洗数据。
        2. 命名实体识别项目，BERT+正则表达式。利用正则表达式匹配邮箱学校名称这些。
        输入是一个txt,把PDF文件转化为txt，pdfminer，OCR（crnn）
        3. 金融文本识别，BERT+BILSTM+CRF。
        问题：
            1.为什么要加BiLSTM? 深度学习相关
            2.crf不是特别了解。 过程，求解
## 四、实习经历4
    实习地点：北京望京
    实习公司：小浆科技
    实习时间：2019-07-16-2019-08-26
    实习内容：
        1.在superset上配置报表（sql),留存，新增用户数，人均观看时长，人均观看次数，语音数，点赞数，分享数等核心指标。
        2.编写notebook脚本日报，利用python连接mysql，hive，presto。
        3.监测拉新、留存等核心指标。分析AB实验的效果，验证推送策略是否可行。
        埋点事件：app_start,ad_show,client_show,video_play,video_effective_play,video_over,share,audio,like
