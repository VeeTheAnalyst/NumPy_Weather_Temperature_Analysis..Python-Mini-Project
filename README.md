# NumPy_Weather_Temperature_Analysis..Python-Mini-Project

A PSG(Python Study Group) mini project focused on using NumPy for temperature data analysis, performing numerical operations, and comparing weather data across different locations.

---

## Project Overview

This project is a beginner-to-intermediate NumPy data analysis project focused on analyzing weather temperature data.

The project demonstrates how Python lists can be converted into NumPy arrays and how NumPy can be used to perform numerical calculations. The analysis includes inspecting arrays, calculating temperature differences, increasing temperatures, and comparing temperature data from different locations.

---

## Project Objectives

The main objectives of this project were to:

* Import and use NumPy.
* Convert Python lists into NumPy arrays.
* Understand 1D and 2D arrays.
* Identify array dimensions, shape, size, and data type.
* Perform element-by-element numerical operations.
* Compare recorded temperatures with target temperatures.
* Analyze temperature differences between Lagos and Abuja.
* Interpret numerical results and identify key findings.
* Demonstrate the usefulness of NumPy for numerical data analysis.

---

## Technologies Used

* **Python**
* **NumPy**
* **Jupyter Notebook**

---

## Dataset

The project uses temperature observations recorded over seven days.

The main temperature dataset is:

```python
temperatures = [27.5, 29.0, 30.5, 28.0, 31.0, 32.5, 30.0]
```

The project also includes target temperatures and temperature data from three locations:

* Lagos
* Abuja
* Ibadan

---

## Data Conversion and Array Inspection

The temperature data was converted from a Python list into a NumPy array.

The resulting array was inspected to determine:

* Number of dimensions
* Shape
* Data type
* Number of observations

The main temperature dataset is a **1D array** containing **7 observations**, with a data type of **float64**.

---

## Numerical Operations

NumPy was used to perform several numerical operations without manually processing each value.

### Temperature Difference

The recorded temperatures were compared with the target temperatures by subtracting the target values from the recorded values.

```text
[-0.5  1.   1.5  0.   1.   2.5  1. ]
```

### Increasing Temperatures

Each recorded temperature was increased by **2°C** using NumPy array arithmetic.

```text
[29.5 31.  32.5 30.  33.  34.5 32. ]
```

---

## Lagos vs Abuja Comparison

Temperature data from Lagos and Abuja was compared using NumPy.

The difference between Lagos and Abuja temperatures was:

```text
[ 2.  1.  1. -2. -1.]
```

A positive value indicates that Lagos recorded a higher temperature, while a negative value indicates that Abuja recorded a higher temperature for that day.

### Comparison

* **Day 1:** Lagos recorded a higher temperature.
* **Day 2:** Lagos recorded a higher temperature.
* **Day 3:** Lagos recorded a higher temperature.
* **Day 4:** Abuja recorded a higher temperature.
* **Day 5:** Abuja recorded a higher temperature.

---

## Key Findings

1. The highest recorded temperature in the seven-day dataset was **32.5°C on Day 6**.

2. The recorded temperature was above the target temperature on **Days 2, 3, 5, 6, and 7**.

3. Lagos recorded higher temperatures than Abuja during the **first three days**, while Abuja recorded higher temperatures during **Days 4 and 5**.

4. NumPy made it possible to perform calculations across the temperature arrays without manually processing each value.

---

## Project Screenshots

### 1. Temperature Analysis

<img width="1829" height="762" alt="Screenshot 2026-09-19 225503" src="https://github.com/user-attachments/assets/eda2c298-9724-4119-bf30-ec4ca3338270" />
<img width="1840" height="763" alt="Screenshot 2026-09-19 225552" src="https://github.com/user-attachments/assets/5a40d428-72a8-4880-8a03-527a702b35ab" />


```text
![Temperature Analysis](screenshots/temperature_analysis.png)
```

### 2. Lagos vs Abuja Comparison

<img width="1842" height="763" alt="Screenshot 2026-09-19 225807" src="https://github.com/user-attachments/assets/9a3f8b28-ed0a-4deb-ba75-f0d649cc0ce8" />


```text
![Lagos vs Abuja Comparison](screenshots/lagos_vs_abuja.png)
```

### 3. Notebook / Project Report Output

<img width="1844" height="694" alt="Screenshot 2026-09-19 230002" src="https://github.com/user-attachments/assets/d78abfaf-4585-4c7d-b043-c01f18c78fc5" />


```text
![Project Output](screenshots/project_output.png)
```

---

## Project Files

```text
numpy-weather-temperature-analysis/
│
├── NumPy_Weather_Temperature_Analysis.ipynb
├── README.md
│
└── screenshots/
    ├── temperature_analysis.png
    ├── lagos_vs_abuja.png
    └── project_output.png
```

---

## Key Learning Outcomes

Through this project, I practiced:

* Working with NumPy arrays.
* Understanding array dimensions and data types.
* Performing element-wise calculations.
* Comparing numerical datasets.
* Using arrays for practical data analysis.
* Interpreting numerical results instead of simply displaying outputs.
* Applying NumPy to a real-world-style weather analysis scenario.

---

## Conclusion

This project demonstrated how NumPy can be used to convert Python lists into numerical arrays and perform numerical analysis.

The analysis covered array inspection, temperature differences, temperature adjustments, and comparisons between locations. It also provided practical experience in interpreting numerical results and using NumPy as a tool for data analysis.

---

## Author

**Nnadiukwu Glory Vivian** 
Junior Data Analyst

**Email:** gloryvivian2000@gmail.com 

**LinkedIn:** https://www.linkedin.com/in/glory-nnadiukwu-178100322?utm_source=share_via&utm_content=profile&utm_medium=member_ios

---

## Acknowledgements

Special thanks to **Coach Timothy** and **SmartBizCrux Technologies** for providing the hands-on NumPy practice exercise and guidance that made this project possible.

This project was completed as part of my continued learning and practical development in **Python and Data Analytics**.
