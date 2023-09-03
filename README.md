# Advisor Student Data

This repository contains the dataset of 13,936 graduate students majoring in computer science at the top 25 North American universities we collected in 2022 and analyzed in this paper:

**Title**: "Diversity Dilemmas: Uncovering Gender and Nationality Biases in Graduate Admissions Across Top North American Computer Science Programs"

**Authors**: Ghazal Kalhor, Tanin Zeraati, Behnam Bahrak

**DOI**: https://doi.org/10.48550/arXiv.2302.00589

If you use this dataset in your work, please cite our paper:

Kalhor, G., Zeraati, T. & Bahrak, B. Diversity dilemmas: uncovering gender and nationality biases in graduate admissions across top North American computer science programs. *under review at EPJ Data Science* (2023). https://doi.org/10.48550/arXiv.2302.00589

# Dataset

We collected the following information for each student:

* University
* Advisor ID
* Advisor Academic Rank
* Advisor Gender
* Advisor Home Country
* Advisor Standard Field
* Advisor Previous Universities
* Advisor Citation Count
* Advisor h-index
* Advisor Publication Count
* Advisor First Paper Year
* Student ID
* Student Degree
* Student Start Year
* Student Gender
* Student Home Country
* Student Previous Universities

```python
import pandas as pd

students = pd.read_csv('advisorStudent.csv')
students.head(3)
```

University|	Advisor ID|	Advisor Academic Rank|	Advisor Gender|	Advisor Home Country|	Advisor Standard Field|	Advisor Previous Universities|	Advisor Citation Count|	Advisor h-index|	Advisor Publication Count|	Advisor First Paper Year|	Student ID|	Student Degree|	Student Start Year|	Student Gender|	Student Home Country| Student Previous Universities|
|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|
|Caltech|	advisor0|	Professor|	Male|	United States|	Computer systems organization|	University of St. Thomas/University of California, Berkeley/University of California, Berkeley|	6798| 44| 307|	2002|	student0|	PhD| 2017|	Female|	United States|	Rice University|
|Caltech|	advisor0|	Professor|	Male|	United States|	Computer systems organization|	University of St. Thomas/University of California, Berkeley/University of California, Berkeley|	6798| 44| 307|	2002|	student1|	PhD| 2010|	Female|	China|	University of Science and Technology of China|
|Caltech|	advisor0|	Professor|	Male|	United States|	Computer systems organization|	University of St. Thomas/University of California, Berkeley/University of California, Berkeley|	6798| 44| 307|	2002|	student2|	PhD| 2017|	Female|	United States|	University of Nebraska - Lincoln|
