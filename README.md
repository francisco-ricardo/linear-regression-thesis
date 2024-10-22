## Thesis Summary: Linear Regression in the Manufacturing of Printed Circuit Boards

This research focuses on applying **Linear Regression** as part of a Data Mining process to predict the **drilling cycle time** in the manufacturing of printed circuit boards (PCBs). The study involved building a database with real cycle times and developing software to extract complex, low-level data from numeric control programs.

The data were divided into training and testing groups to build a prediction model. The initial Linear Regression model yielded a standard error of **8.321 minutes**, which was higher than the target of **2.0 minutes**. To improve the results, the Linear Regression model was compared with two other algorithms: **M5 Model Trees** and **M5 Rules**, which produced standard errors of **6.525 minutes** and **8.555 minutes**, respectively. However, the dataset was found to be insufficiently representative for an optimal prediction model.

During the research, I deepened my expertise in **Python**, especially in advanced aspects of the language and tools for data extraction. This included using libraries such as **NumPy**, **NumExpr**, and **Matplotlib** for data manipulation and visualization, as well as developing complex **regular expressions** to efficiently process and extract data. The study also utilized the **Weka** framework, which was common at the time but has since been largely replaced by more modern tools like **TensorFlow** and **PyTorch**.

Despite the challenges, the research provided valuable insights into the manufacturing process. The extracted data led to the development of algorithms to calculate **drill tool consumption**, the number of drill bits used per slot and nibble, and the optimization of the drill path.

All technologies used in this research are public domain and met the research goals, enhancing the understanding and control of the PCB manufacturing process.

**Keywords**: Linear Regression, Data Mining, Manufacturing, Printed Circuit Boards, Cycle Time Prediction, Machine Learning, Python, NumPy, Weka, TensorFlow, PyTorch.
