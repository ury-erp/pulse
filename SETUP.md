  ## URY Pulse Setup 

Follow these steps to set up URY Pulse after completing basic ERPNext configuration:

#### Step 1 : 

- Complete all the steps outlined in the [URY Setup](https://github.com/ury-erp/ury/blob/main/SETUP.md)

#### Step 2:

- Navigate to **URY Report Settings** in  your site. 
- Click on **Add URY Report Settings**.

#### Step 3

- Under the **Details** tab:
    - **Extended Hours** : Enable this if the branch operates after 12 AM.
    - **No of Hours** : Enter the number of hours, if extended hours is enabled. 
- Under the **Daily P and L Settings** tab:
    - **Buying price List** : Select the buying price list for your branch.
        - Under **Direct Expenses**:
            - **Burning Materials (Other Consumables)** : Table to list consumables.
                - **Material** : Enter the Material (e.g., gas, charcoal).
                - **Cost Per Unit** : Specify the cost per unit for each material.
            - **Direct Fixed Expenses** : Table to add list of daily fixed direct expenses.
                - **Expense** : Provide the expense name.
                - **Amount** : Specify amount for each expense.
        - Under **Indirect Expenses**:
            - **Electricity Charges**: Enter the electricity charges per unit.
            - **Indirect Fixed Expenses** : Table to list daily fixed indirect expenses.
                - **Expense** : Provide the expense name.
                - **Amount** : Specify amount for each expense.
            - **Percentage Expenses** : Table to list of expenses as a percentage of sales.
                - **Expense** : Provide the expense name.
                - **Percentage Type** : Choose the percentage type (Net Sales or Gross Sales).
                - **Percent** : Specify the percentage of the selected type.
        - Under **Employee Costs**:
            - **Employee Costs** : Table to list daily fixed expenses as a part of employee costs.
                - **Expense** : Provide the expense name.
                - **Amount** : Specify amount for each expense.
    - **Depreciation** : Add depreciation amount if applicable.


  ### Daily Gross Salary Cost is calculated from employees attendance.

Follow these steps to set up the payment type and payment amount for employees:

#### Step 1:

- Navigate to **Employee** in  your site. 
- Choose the relevant **Employee**.

#### Step 2:

- Under the **Salary** tab:
    - **Payment Type** : Choose between Salary or Daily Wage.
    - **Payment Amount** : Enter the corresponding payment amount. 


Follow the [Attendance documentation](https://frappehr.com/docs/v14/en/attendance#3-features) for marking the attendance or use the [Employee Attendance Tool](https://frappehr.com/docs/v14/en/employee-attendance-tool#2-how-to-mark-attendance-using-employee-attendance-tool)