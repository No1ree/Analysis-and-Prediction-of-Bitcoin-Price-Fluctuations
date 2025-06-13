# Analysis-and-Prediction-of-Bitcoin-Price-Fluctuations
Analysis and Prediction of Bitcoin Price Fluctuations Based on LSTM
项目概述
这个项目是一个全面的比特币分析系统，结合了多种技术分析指标、统计模型和深度学习预测算法，对比特币市场行为进行多角度研究和未来价格预测。系统不仅提供历史价格模式和波动性分析，还利用先进的LSTM-Attention模型进行未来价格趋势预测。

核心功能
1. 全面市场分析
​​价格趋势分析​​：多时间尺度价格趋势、回报率分布
​​成交量分析​​：交易量季节性、交易量与价格变动关系
​​波动率分析​​：波动率聚集效应、布林带分析、GARCH建模与预测
​​收益率分析​​：收益分布统计特性、月度收益率模式
​​相关性分析​​：价格与成交量相关性、量价关系研究

3. 技术指标应用
​​相对强弱指数(RSI)​​：识别超买超卖区域
​​移动平均收敛发散(MACD)​​：捕捉市场动量变化
​​布林带(Bollinger Bands)​​：测量市场波动性
​​价格通道(Price Channels)​​：识别支撑位和阻力位
​​多移动平均分析​​：金叉/死叉交易信号检测

5. 深度学习价格预测
​​Bidirectional LSTM + Attention模型​​：捕捉复杂时间序列模式
​​递归多步预测​​：未来30天价格趋势预测
​​预测不确定性量化​​：RMSE和95%置信区间
​​三维可视化分析​​：历史表现与未来趋势联合展示

技术栈
​​编程语言​​：Python
​​核心库​​：
NumPy, Pandas - 数据处理
Matplotlib, Seaborn - 数据可视化
Scikit-learn - 数据预处理
TensorFlow/Keras - 深度学习建模
ARCH - 波动率建模

​​统计方法​​：
ADF检验
季节性分解
GARCH(1,1)模型
自相关分析
