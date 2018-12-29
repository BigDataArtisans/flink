## 2018-12-21周会
### 上周跟进
- 已完成。晋级事项
- 已完成。元旦，春节值班人员
- 待维护。OKR攻坚文档记录

### 周会内容
- **下周分享** 郭昌佶提前申请二维码&订会议室；督促听众 报名/签到/评分
- 本周iowait问题定位以及相关解决方案落实
- Q1工作OKR制定以及沟通确认
- Sqoop任务问题过堂及定位
-

### 下周跟进事项
- 改完socketTimeout, sqoop worker 目前出现501,

### 风险点
-

### 纪要
- OKR攻坚文档记录



<br>
<br>
<br>

---

1. 跟进checkpoint时长问题，10min，模拟环境，定位问题
2. 修复flink1.6.x版本 固定重启策略，间隔时长为0, 导致程序卡死问题，已提交
3. 跟进elsticsearch5.x-connector-trainsport线程泄露问题，根本原因已找到，netty为close，修复复杂
   netty完成初始化，紧接着进行检测每个 host，未有可用节点，直接抛runntime，但是netty未释放
4. kakfa的checkpoint，不能恢复至算子的异常定位，未解决。在模拟
5. 吕为盛、黄淦，解释main方法log4j日志问题，属于解析层，不会体现在log中
6. 交通尚苏定位依赖问题，provided
7. 酒店何富贵，flink打样协助
8. 解决timeout sqoop进程问题，采用生乾找到的命令打样，










  

  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  















