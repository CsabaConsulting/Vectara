Question: What is the purpose of the "Accounts Receivable Weeks to Collect" category?
Answer: The purpose of the "Accounts Receivable Weeks to Collect" category is to determine the time period over which the beginning accounts receivables will be collected in cash. It allows for the even collection of the beginning accounts receivables over a specified time. This category also provides the option to input the average weeks to collect for future years, which will be used for calculating the collection of accounts receivables beyond the beginning balances. Additionally, it allows for the calculation of a weighted average for the weeks to collect if the existing company is purchasing a target company in Year 1. The category provides flexibility in setting up and managing the collection of accounts receivables for both current and future periods.
---
Question: How is the collection of Beginning A/R balances distributed over time?
Answer: The collection of Beginning A/R balances is evenly distributed over a specified time period. The time period is determined by the input for "Accounts Receivable Weeks to Collect" in the Accounts Receivable Set Up pages for the Transaction Sheet and the Existing Company Accounts Receivable Beginning Balances. 
If no input is provided for the Beginning A/R balances, or if it is left blank, a default value of 0 will be used. In this case, all sales will be collected in the sale period.
It is important to note that this distribution of Beginning A/R balances only applies to the Beginning A/R balances. For future years, the input for "Accounts Receivable Future Weeks to Collect" in the Accounts Receivable - Future Terms Set-Up Input page will be used. If there is no input for future years, the input for the Beginning A/R balance will be used as the default value. 
In the case of an Existing Company purchasing a Target Company, a weighted average will be calculated for Year 1 between the Weeks to Carry listed on the Transaction Sheet for the Target Company and the Weeks to Carry for the Existing Company. For subsequent years, the input for Ave Weeks to Collect in the Future Input will be used without any weighted average calculation. If there are no inputs for Ave Weeks to Collect in the Future and no selection indicated in the Transaction Sheet, the entry for the Existing Company will be used for future years.
---
Question: What happens if there is no selection for future years in the "Future Ave Weeks to Collect" input?
Answer: If there is no selection for future years in the "Future Ave Weeks to Collect" input, the default value for future years will be the input for the Beginning A/R balance. This means that the number of weeks it takes to collect accounts receivable in the future years will be the same as the number of weeks it takes to collect the beginning accounts receivable balance. If the Beginning A/R balance is left blank or set to 0, it means that all sales will be collected in the sale period and there will be no outstanding accounts receivable.
---
Question: What is the default value for future years if the "Beginning A/R balance" input is left blank?
Answer: If the "Beginning A/R balance" input is left blank, the default value for future years will be 0. This means that all sales will be collected in the sale period and there will be no outstanding accounts receivable beyond that period.
---
Question: How is the weighted average calculated for Year 1 if the Existing Company is purchasing the Target Company?
Answer: For Year 1, if the Existing Company is purchasing the Target Company, the weighted average for the Weeks to Carry will be calculated. This calculation is based on the Weeks to Carry listed on the Transaction Sheet for the Target Company and the Weeks to Carry for the Existing Company. The weighted average is used to determine the average number of weeks it will take to collect the accounts receivable for Year 1. 
Please note that for Years after Year 1, the Ave Weeks to Collect in the Future Input will be used without any weighted average calculation. If there are no inputs for the Ave Weeks to Collect in the Future and no selection indicated in the Transaction Sheet, the entry for the Existing Company will be used for future years.
---
Question: What input is used for future years if there are no inputs in the "Ave Weeks to Collect in the Future" and no selection indicated in the Transaction Sheet?
Answer: If there are no inputs in the "Ave Weeks to Collect in the Future" and no selection indicated in the Transaction Sheet, the entry for the Existing Company will be used for future years.
---
Question: Where can the "Accounts Receivable Weeks to Collect" input be found for the Transaction Sheet and the Existing Company Accounts Receivable Beginning Balances?
Answer: The "Accounts Receivable Weeks to Collect" input can be found in the Accounts Receivable Set Up pages for both the Transaction Sheet and the Existing Company Accounts Receivable Beginning Balances.
---
Question: What does the "Accounts Receivable Future Weeks to Collect" input apply to?
Answer: The "Accounts Receivable Future Weeks to Collect" input applies to the number of weeks on average that the Accounts Receivables will be outstanding in the future Horizon Period years selected by the User. It is used to determine the time it takes for the company to collect cash from its customers for sales made on credit. This input is found in the Accounts Receivable - Future Terms Set-Up Input page.
---
Question: How are Weeks to Collect defined for Accounts Receivables?
Answer: Weeks to Collect for Accounts Receivables refers to the average number of weeks it takes for the company to collect payment for outstanding invoices. This metric is used to estimate the time it will take to convert accounts receivable into cash. 
In the context of the provided documentation, there are two components related to Weeks to Collect: Beginning Accounts Receivables and Future Weeks to Collect.
1. Beginning Accounts Receivables: This refers to the time period over which the beginning accounts receivables balance will be collected in cash. The collection is evenly spread over this specified time period. If no value is provided for this input, a default value of 0 will be used, indicating that all sales will be collected in the sales period.
2. Future Weeks to Collect: This input is used for future years beyond the beginning accounts receivables period. It represents the average number of weeks that accounts receivables are expected to be outstanding in those future years. The user can specify this value on the Accounts Receivable - Future Terms Set-Up Input page. It should be a whole number and not a fraction of a week.
It is important to note that if there are no inputs provided for the future weeks to collect and no selection indicated in the transaction sheet, the value entered for the existing company will be used for future years. Additionally, if the existing company is purchasing a target company, a weighted average calculation will be performed for Year 1 using the weeks to carry values from both companies.
---
Question: What should be the format of the input for "Accounts Receivable Future Weeks to Collect"?
Answer: The input for "Accounts Receivable Future Weeks to Collect" should be a whole number and not a portion of a week.
