# Business Case Study: Developing a Power BI Dashboard for Global Benchmarking Data
## Data Professional Survey Breakdown

### Client Requirement: 
A dataset containing responses from professionals worldwide on various aspects of their careers, focusing on data roles. The objective was to build a Power BI dashboard that presents comprehensive insights into employee happiness, career transitions, and demographic data The client requested a three-page dashboard, including embedded links for gender-specific insights.

### Dataset Overview:

The dataset consists of multiple columns capturing participant details:

-   **Demographics**: Gender, Age, Country, Ethnicity, Education Level

-   **Professional Information**: Current Role, Industry, Salary, Career Transition

-   **Satisfaction Levels**: Happiness Index on Salary, Work/Life Balance, Coworkers, Management, Upward Mobility, Learning Opportunities

-   **Additional Insights**: Preferred Programming Language, Difficulty in Transitioning to Data Roles, Most Important Factors in Job Search

### Solution Development:

1.  **Data Cleaning and Transformation:**

    -   **Data Consistency:** Addressed inconsistencies in text entries, standardized responses, and ensured uniformity in categorical variables.

    -   **Missing Values:** Handled missing entries, especially in demographic fields like education and ethnicity, through imputation or omission, depending on the context.

    -   **Date-Time Conversion:** Converted date and time columns from text format to appropriate datetime formats for accurate analysis.

2.  **Data Modeling:**

    -   **Relationships:** Established relationships between key tables in Power BI, such as linking demographic data with survey responses, using unique identifiers.

    -   **Measures using DAX:**

        -   **Happiness Index:** Created a calculated measure to aggregate participant satisfaction across various factors (e.g., Salary, Work/Life Balance).

        -   **Average Salary by Role:** A DAX formula was used to compute the average salary based on different roles.

        -   **Career Transition Difficulty:** Analyzed the distribution of responses regarding the difficulty of transitioning into data roles.

3.  **Dashboard Design:**

    -   **Page 1: Overview of Key Insights**

        -   **Employee Happiness Index:** A composite score visualized using a bar or gauge chart.

        -   **Current Role Distribution:** Displayed using a pie chart or a bar chart.

        -   **Average Salary by Role:** Presented with a column chart.

        -   **Career Transition Difficulty:** Visualized using a stacked bar chart.

        -   **Most Important Factor in Job Search:** Highlighted through a word cloud or bar chart.

        -   **Demographics:** Country, Education, Industry, and Preferred Programming Languages shown in respective visuals (maps, bar charts).

        -   **Embedded Links:** Navigation buttons to pages for male and female respondents.
        
        -   <img width="805" alt="image" src="https://github.com/user-attachments/assets/d3cc53f5-bfb3-45c7-9615-2ba1869617bc">

    -   **Page 2: Male Respondents\' Insights**

        -   Detailed breakdown of male respondents\' data, focusing on happiness, salary, and professional transitions.
          
        -   <img width="805" alt="image" src="https://github.com/user-attachments/assets/ffa71ae3-10f2-4acf-bc90-db8f04798dfa">

  -   **Page 3: Female Respondents\' Insights**

        -   Similar to Page 2, but focused on female respondents.
   
        -   <img width="805" alt="image" src="https://github.com/user-attachments/assets/1fdb89f9-4a46-4e86-9bb0-0df6a44aedb4">


### Results:

The Power BI dashboard delivered comprehensive insights into the global dataset, enabling stakeholders to:

-   Identify trends in employee happiness across different roles and industries.

-   Understand challenges faced by professionals transitioning into data roles.

-   Gain visibility into the most valued aspects of new job opportunities across genders.

**Impact:**

-   **Decision-Making:** The client leveraged the dashboard to inform strategies for improving employee satisfaction and tailoring recruitment efforts.

-   **Actionable Insights:** Enabled the organization to address gender-specific needs in the workplace by visualizing distinct patterns in satisfaction and career preferences.

The project showcases the power of data-driven insights in shaping organizational strategies, with a focus on employee well-being and career progression.

## Link To Live Dashboard
[Data Professionals Survey Breakdown - Kaif Abbas](https://app.powerbi.com/view?r=eyJrIjoiOWY1ZjA4ZWUtNTkzNy00NTcwLTgxM2ItMGFjOWZiOWRhNDdjIiwidCI6ImY5NjA5ZDEyLTcyYzgtNDZiZS05OWQ4LTYyN2U3YTYwYWIyMSJ9&pageName=ReportSection)

## Video


