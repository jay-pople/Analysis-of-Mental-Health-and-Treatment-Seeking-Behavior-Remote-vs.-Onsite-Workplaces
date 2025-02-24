# Analysis-of-Mental-Health-and-Treatment-Seeking-Behavior-Remote-vs.-Onsite-Workplaces

## Overview:
The main goal of this project is to analyze and compare the mental health conditions of remote and onsite workers, focusing on their treatment-seeking behavior. The study aims to identify whether working remotely or onsite has an impact on individuals seeking professional help for mental health issues.

## Files:
- **Mental_Health_Analysis.inynb**
- **dataset.csv**

## Requirements:
- **Python version:** 3.13.0
- **Jupyter lab version:** 4.2.3

## Analysis Conducted:

1. Which country has the highest number of responses?
2. What is the gender-wise distribution of treatment sought?
3. Is there any difference between people taking treatment in remote vs. onsite work settings?
4. What is the distribution of treatment-seeking behavior with respect to family history of mental health issues?
5. What is the age-wise distribution of people who take treatment vs. those who do not?
6. Does mental health interfere with people’s work?
7. What is the distribution of workplace size in both remote and onsite work modes?
8. Are remote workers in smaller workplaces more prone to not taking treatment?
9. Are people more likely to take treatment if mental health care options are offered at the workplace?
10. What is the probability that a person will take treatment given that a wellness program is offered at the workplace?

## Dataset Import & Transformation
### Data Processing Steps:
1. **Importing the Dataset**
2. **Data Transformation:**
   - Removing irrelevant features.
   - Standardizing values in relevant categories.
   - Imputing missing values.

## Key Findings
- **Work Mode Distribution:** 70.1% of respondents work onsite, while 29.9% work remotely.
- **Treatment-Seeking Behavior:** Nearly identical between remote and onsite workers.
- **Workplace Support:** Wellness programs and mental health care options at workplaces increase treatment-seeking likelihood.
- **Family History Influence:** Individuals with a family history of mental health issues are more likely to seek help.
- **Demographic Trends:** Younger individuals and males show a lower tendency to seek treatment despite reporting mental health concerns.
- **Geographical Bias:** The dataset primarily reflects U.S.-based respondents, emphasizing the need for targeted mental health support, especially in large workplaces and among underrepresented groups.

## Conclusion
The analysis underscores the importance of workplace mental health initiatives and highlights key demographic and historical factors influencing treatment-seeking behavior. Organizations can leverage these insights to develop better mental health support structures.

## Repository Structure
- `data/` - Contains the dataset used for analysis.
- `notebooks/` - Jupyter notebooks for data exploration and visualization.
- `src/` - Scripts for data processing and analysis.
- `README.md` - Project documentation.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mental-health-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd mental-health-analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the analysis notebooks or scripts to explore the findings.

