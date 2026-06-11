# Data Analysis Dashboard Project

## Project Title : AI Student Impact Analysis Dashboard

---

## Project Objective

The objective of this project is to analyze the impact of Generative Artificial Intelligence (GenAI) on students' academic performance, learning outcomes, study habits, and overall well-being. The dashboard explores how students interact with AI tools and examines the relationships between AI usage, academic success, skill retention, anxiety levels, and burnout risk.

---

## Data Description

As Generative AI tools like ChatGPT, Copilot, and Gemini become deeply embedded in academic life, understanding their true impact on students has never been more critical. This dataset provides a rich, multi-dimensional snapshot of student interactions with AI, spanning academic outcomes, behavioural patterns, institutional context, and psychological well-being.

---

## Features

| Variable                   | Description                       |
| -------------------------- | --------------------------------- |
| Student_ID                 | Unique student identifier         |
| Major_Category             | Academic discipline               |
| Year_of_Study              | Student's year of study           |
| Pre_Semester_GPA           | GPA before the semester           |
| Weekly_GenAI_Hours         | Weekly hours spent using AI tools |
| Primary_Use_Case           | Main purpose of AI usage          |
| Prompt_Engineering_Skill   | Prompt-writing proficiency level  |
| Tool_Diversity             | Number of AI tools used           |
| Paid_Subscription          | AI subscription status            |
| Traditional_Study_Hours    | Weekly non-AI study hours         |
| Perceived_AI_Dependency    | Self-reported dependence on AI    |
| Institutional_Policy       | Institution's AI policy           |
| Anxiety_Level_During_Exams | Student exam anxiety level        |
| Post_Semester_GPA          | GPA after the semester            |
| Skill_Retention_Score      | Knowledge retention score         |
| Burnout_Risk_Level         | Burnout risk classification       |

---

## Data Preparation

The following steps were performed before analysis:

* Checked for missing values
* Removed duplicate records
* Verified data types
* Examined outliers
* Created derived metrics for deeper analysis

---

## Data Transformation

### GPA Change

```text
Post_Semester_GPA - Pre_Semester_GPA
```

### AI Usage Categories

* Low Usage
* Medium Usage
* High Usage

### Study Balance Ratio

```text
Weekly_GenAI_Hours / Traditional_Study_Hours
```

---

## Dashboard Components

### KPI Cards

* Average AI Usage Hours
* Average Pre-Semester GPA
* Average Post-Semester GPA
* Average GPA Improvement
* Average Skill Retention Score

### Visualizations

1. **AI Usage by Major Category**
   - Compares average GenAI usage across different academic disciplines.

2. **Primary AI Use Case by GPA Change**
   - Examines how different AI use cases relate to changes in academic performance.

3. **Burnout Risk Distribution**
   - Shows the proportion of students classified as High, Medium, and Low burnout risk.

4. **GPA Improvement by AI Usage Intensity**
   - Compares GPA improvement among Low, Medium, and High AI users.

5. **AI Dependency vs Skill Retention**
   - Analyzes the relationship between perceived AI dependency and knowledge retention.

6. **Prompt Engineering Skill vs GPA**
   - Evaluates how prompt engineering proficiency influences academic performance.

---

### Interactive Filters (Slicers)

- Year of Study
- Major Category
- Burnout Risk Level
- Paid Subscription Status

---

## Key Insights

### Academic Performance

* Students generally showed improvement in GPA after the semester.
* Moderate AI users achieved the highest academic gains.
* Strong prompt engineering skills were associated with better academic outcomes.

### Learning Outcomes

* Higher AI dependency was linked to lower skill retention scores.
* Students who used AI as a learning aid retained knowledge better than those who relied on it heavily for task completion.

### Study Habits

* Increased AI usage was associated with reduced traditional study hours.
* Students using a wider variety of AI tools demonstrated stronger academic performance.

### Student Well-being

* Moderate AI usage was associated with lower exam anxiety.
* High perceived AI dependency corresponded with increased burnout risk.

---

## Recommendations

* Encourage responsible and balanced AI usage among students.
* Provide training on effective prompt engineering techniques.
* Promote AI as a learning support tool rather than a replacement for independent study.
* Develop institutional guidelines to support ethical and productive AI adoption.
* Monitor excessive AI dependency to reduce burnout risks and preserve learning outcomes.

---

## Tools Used

* Microsoft Excel
* Pivot Tables
* Pivot Charts
* Dashboard Design
* GitHub Markdown Documentation

---

## Dashboard Preview

<img width="1911" height="1008" alt="image" src="https://github.com/user-attachments/assets/0336b7fa-9bb7-4e42-ac23-4a7fb30cd206" />

---

## Conclusion

The analysis demonstrates that Generative AI can positively influence student performance when used strategically and in moderation. However, excessive dependency may negatively affect skill retention and increase burnout risk. Educational institutions should focus on promoting responsible AI usage while maintaining strong independent learning practices.
