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
    - **Depreciation** : Add depreciation amount if applicable.