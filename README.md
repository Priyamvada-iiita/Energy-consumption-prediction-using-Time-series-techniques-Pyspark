# Energy-consumption-prediction-using-Time-series-techniques-Pyspark
Data-driven model validated with real-world smart meter data for demand and response-based energy consumption for smart buildings with Big data Analytics

Introduction:
Amidst increasing global energy demand and environmental security concerns, the imperative for developing more efficient energy systems has intensified. A compelling avenue lies in smart homes equipped with cutting-edge technology and communications. This study harnesses big data analytics to advocate for a data-driven approach to modeling and optimizing demand response based on energy utilization in smart buildings. Leveraging data from smart meters worldwide, we aim to develop and evaluate predictive models capable of forecasting energy demand and adjusting energy usage potential in response to grid prices or peak demand periods. The project aims to showcase how big data-driven analytics can enhance energy management in smart buildings, thereby trimming energy costs and refining grid regulation. We utilized the PySpark's MLlib framework for forecasting future demand to align resources with performance.

Conclusion:

In summary, although GBT exhibited superior performance during training, RF outperformed during testing without validation, suggesting that RF is the optimal choice. Interestingly, GBT's training results are not inferior to RF's. However, it is apparent that the simplicity of horizontal lines yields the best performance.

In general, the first method yields superior results, with GBT achieving an RMSE of approximately 0.0027 and a MAPE of 28%, while RF only narrows the MAPE by 15%. Nonetheless, the second model cannot be discounted entirely, as the first method includes additional features leaking vital information such as voltage and average current. Real-life scenarios typically only provide time records.

The initial data model leverages intelligent data connectivity to address the practical needs of major energy users, including appropriate products and electrical backup and storage systems for fire trucks. By carefully monitoring supply and time, we can predict demand accurately. However, due to limited data availability for our specific research, our focus lies in predicting future demand (customers), enabling us to organize resources and production to meet supply demands. Considering the significance of temperature and humidity in this process, factors like temperature, humidity, holidays, and festivals are incorporated. Multiple time comparison test samples can further enhance subsequent analyses.

Refer Group_10_C3_BDA_REPORT.pdf for more information
