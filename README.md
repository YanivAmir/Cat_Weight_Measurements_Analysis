### Overview:
Data is provided from two weight bases placed under litter boxes in a pet-owner household with two cats. These bases measure weight and are designed to help monitor the health and habits of the pets. The sensors log data either when there is a weight change of at least 20 grams or every three minutes to provide a baseline health check.

### Data Description:
The dataset includes timestamps, weight changes, raw weight values, and device identifiers. the data is noisy and should be cleaned/baselined.

### Objective:
Analyze the data to determine the operation status of the bases, identify and analyze litter box visits, and specifically monitor the weight changes of one of the cats.

### Tech Used in Analysis:

<img alt="Python" src="https://img.shields.io/badge/Python-3776ab?logo=python&logoColor=white&style-flat"><img alt="scikit-learn" src="https://img.shields.io/badge/Scikit-f7931e?logo=scikit-learn&logoColor=white&style-flat">
<img alt="NumPy" src="https://img.shields.io/badge/NumPy-013242?logo=numpy&logoColor=white&style-flat">
<img alt="Pandas" src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white&style-flat">
<img alt="SciPy" src="https://img.shields.io/badge/SciPy-8CAAE6?logo=SciPy&logoColor=white&style-flat">
<img alt="Jupyter" src="https://img.shields.io/badge/Jupyter-f37626?logo=jupyter&logoColor=white&style-flat">
<img alt="PyCharm" src="https://img.shields.io/badge/PyCharm-000000?logo=PyCharm&logoColor=white&style-flat">

### Sample Results:

![image](https://github.com/user-attachments/assets/453b3fc9-03fc-4850-a9dd-20ac1f57ee63)
Cat A Metric Distribution

![image](https://github.com/user-attachments/assets/888f4adb-11fc-4b73-b3ea-03d8e4d3a2c9)

Cat A that uses the office litter box was ~5.75kg when measurement started. According to the measurements and calcualtions it has reduced 300gr in weight during the measuring period, which are equal to a ~4gr daily average wieght loss.



![image](https://github.com/user-attachments/assets/8448e6d7-22e2-4d4f-b91b-f3722f7493fb)
Cat B Metric Distribution

![image](https://github.com/user-attachments/assets/81e39098-802f-4391-9c0f-db86e6a833e2)

Cat B that uses uses the litter box in the dining room (most of the time) weighted ~4.5kg when the measuremnet started. It appears it also dropped 300gr during this period, which correspond to ~4gr daily.
