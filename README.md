# **Biodiversity in U.S. National Parks**

## **📌 Project Overview**

This repository contains a Jupyter Notebook that explores data from the National Parks Service on endangered species. The analysis investigates patterns of conservation risk across species categories and national parks.

The project demonstrates **data cleaning, exploratory data analysis, aggregation, visualisation, and interpretation**, providing a clear example of a beginner data analyst workflow.

**Research questions explored:**

1. Which conservation statuses are most common across all species?
2. Are certain species categories more likely to be at risk?
3. Which national parks have the highest number of protected species?
4. Are endangered species concentrated in specific parks or spread evenly?

---

## **📊 What This Project Does**

* Loads and inspects species and observations datasets.
* Performs **exploratory data analysis (EDA)** to understand distributions, missing values and duplicates.
* Cleans and merges datasets for accurate analysis.
* Counts and visualises species by conservation status and category.
* Calculates proportions of species at risk by category.
* Examines the distribution of protected and endangered species across national parks.
* Creates clear bar charts to aid interpretation of results.

---

## **📁 Repository Structure**
```
Biodiversity-National-Park/
├── README.md                       # Overview and documentation for this project
├── requirements.txt                # Python dependencies and versions
├── data/
│   ├── observations.csv            # Species observations dataset
│   └── species_info.csv            # Species info dataset with categories and conservation status
└── notebooks/
└── biodiversity.ipynb              # Jupyter Notebook containing full analysis
```    
---



## **📦 Requirements**

Install the required Python packages listed in **requirements.txt** to run the notebook:

```pip install -r requirements.txt```

Dependencies include (but not limited to):

* Python
* pandas
* matplotlib
* jupyter

---



## **📌 Data Sources**

* **Observations dataset:** **observations.csv** – records of species observed in national parks.
* **Species dataset:** **species_info.csv** – contains species categories and conservation status.

*Note:* Scientific names and park names were preserved in their original case to maintain scientific conventions and readability. Only category and conservation status were standardized to lowercase.

---

## **📈 Key Results**

* **Most species are not protected**, with only a small fraction classified as endangered, threatened, or in recovery.
* **Mammals and birds** have the highest proportion of species at risk, while plants and reptiles have lower proportions.
* Protected species are **evenly distributed across parks**, with similar counts per park.
* Endangered species are **spread relatively evenly** across national parks, suggesting standardized reporting or broad ecological coverage.

---

## **🛠️ Tools & Technologies**

This project uses the following tools and libraries:

* Python
* Pandas & NumPy
* Matplotlib 
* Jupyter Notebook
* Git & GitHub

---

## **🔮 Future Work**

Potential extensions include:

* Explore patterns by ecosystem or geographic region
* Include temporal trends using observation dates
* Compare conservation risk across additional species datasets
* Publish cleaned dataset or summary tables for reproducibility

---

## **📜 License**

This project is available under the MIT License. 

---



## **📌 Acknowledgements**

Thanks to the **National Parks Service**  and **Codecademy** for providing the datasets and inspiration for this project.
