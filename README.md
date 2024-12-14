# Data Jobs Analysis

This project analyzes a dataset containing information about data-related job roles, salaries, and other job attributes. Below is the detailed metadata for the dataset.

## Dataset Metadata

### **Columns and Descriptions**

1. **`work_year`**  
   - The year the salary was paid.

2. **`experience_level`**  
   - The level of experience required for the role during the given year. Possible values:
     - **EN**: Entry-level / Junior  
     - **MI**: Mid-level / Intermediate  
     - **SE**: Senior-level / Expert  
     - **EX**: Executive-level / Director  

3. **`employment_type`**  
   - The type of employment for the role. Possible values:  
     - **PT**: Part-time  
     - **FT**: Full-time  
     - **CT**: Contract  
     - **FL**: Freelance  

4. **`job_title`**  
   - The title of the role worked during the year.

5. **`salary`**  
   - The total gross salary amount paid in the specified currency.

6. **`salary_currency`**  
   - The currency of the salary paid, represented using ISO 4217 currency codes (e.g., USD, EUR).

7. **`salary_in_usd`**  
   - The gross salary converted to USD, adjusted based on the average FX rate for the respective year (via fxdata.foorilla.com).

8. **`employee_residence`**  
   - The employee's primary country of residence during the work year, represented using ISO 3166 country codes (e.g., US, DE).

9. **`remote_ratio`**  
   - The percentage of work performed remotely. Possible values:  
     - **0**: No remote work (less than 20%)  
     - **50**: Partially remote  
     - **100**: Fully remote (more than 80%)  

10. **`company_location`**  
    - The country of the employer's main office or contracting branch, represented using ISO 3166 country codes.

11. **`company_size`**  
    - The average size of the company during the year. Possible values:  
      - **S**: Small (less than 50 employees)  
      - **M**: Medium (50 to 250 employees)  
      - **L**: Large (more than 250 employees)  

---

This README provides the necessary details to understand and interpret the dataset, making it a useful resource for data analysis projects.
