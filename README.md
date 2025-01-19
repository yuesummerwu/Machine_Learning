# Why Do Schools Perform Low? Identifying Key Predictors of North Carolina School Performance through Machine Learning :eyes:

This repository stores the project materials for the course **ORLA 6541:  Data Science for Organizations and Leadership** at Teachers College, Columbia University. The project utilzied access and opportunity data to predict school performance. 

In many states, the current accountability systems evaluate school performanced by test scores and lack the consideration of school resources. Therefore, this project aims to consider the previous reserachers' suggestions regarding expanding accountability to more indicators by utilizing machine learning techniques. The logic is if school performance can be predicted by those predictors, that means those school characteristics have a impact on students' test performance and thus school performance. With variable importance index, school leaders can be informed about what to work on as priority to improve their school perforamnce.

## Abstract 📝

This study uses machine learning models—Logistic Regression, Classification Tree, and Random Forest—to classify North Carolina schools as low-performing or high-performing based on publicly available data from the NC Department of Public Instruction. Random Forest achieved the highest AUC (0.7797), with teacher effectiveness, percentage of beginning teachers, and chronic absenteeism identified as the most important predictors. This study highlights the utility of machine learning in analyzing school performance and identifying actionable priorities for school leaders. By providing insights into the relative importance of school inputs, the research offers a diagnostic framework for performance assessment and improvement. Future studies can expand this work by replicating the approach in other states and incorporating additional variables to better understand systemic factors influencing school success.

## Contents 📂

This repository includes the following files and directories:

- **`code/`**: Scripts for data preprocessing, clustering, and visualizations, available in multiple formats, including Markdown, RMarkdown, and HTML. 💻
- - For better preview experiences, please refer to [the HTML](https://yuesummerwu.github.io/Hiarachical_Cluster_Analysis/ORLA6541_Midterm/Code/ORLA6541_Midterm_HCAHeatmap_YueSummerWu.html).
- **`figures/`**: Visual outputs, such as AUC ROC 📊 
- **`paper/`**: An AERA-style proposal in PDF format, complete with figures, tables, and references 📝<br>

***Note:** All data used in this project are publicly accessible from the NC DPI. The provided Markdown files include code that directly retrieves data from the websites, eliminating the need to download datasets beforehand. Feel free to reuse these scripts for other analyses!*
