Question: What is the purpose of the "Inventory Weeks to Hold" category?
Answer: The purpose of the "Inventory Weeks to Hold" category is to determine the average time period for which inventory will be held for use. It is used to calculate the amount of inventory that should be kept on hand, taking into account factors such as production or purchase lead times and sales cycles. The input for "Inventory Weeks to Hold" is used to calculate the inventory levels for the beginning inventory balances. For future years, the input for "Future Ave Weeks to Hold" is used, unless specified otherwise in the transaction sheet. If no selection is made, a default value of 0 will be used, indicating that no inventory will be held for use.
---
Question: How is the average time over which the inventory will be held for use calculated?
Answer: The average time over which the inventory will be held for use is calculated based on the "Inventory Weeks to Hold" input. This input is found in the Inventory Set Up pages for the Transaction Sheet and the Existing Company Inventory Beginning Balances. 
If a value is entered for "Inventory Weeks to Hold," it represents the average number of weeks that the inventory will be held for use. This means that the inventory will be evenly used over this time period. 
If no value is entered for "Inventory Weeks to Hold," or if it is left blank, a default value of 0 will be used. In this case, no inventory will be held for use. 
It's important to note that the calculation of average time over which the inventory will be held for use only applies to the beginning inventory balances. For future years, the input for "Future Ave Weeks to Hold" will be used. If no selection is indicated for future years, the default value will be the selection indicated for the initial inputs on the Transaction Sheet. 
If the Existing Company is purchasing the Target Company, a weighted average will be calculated between the "Weeks to Hold" listed on the Transaction Sheet for the Target Company and the "Weeks to Hold" listed for the initial input for the Existing Company. For years after Year 1, the selections in the "Ave Weeks to Hold" in the Future Input will be used with no weighted average calculation. If there is no selection indicated in the Transaction Sheet, the initial input for the Existing Company will be used for future years.
---
Question: When will the input for "Future Ave Weeks to Hold" be used?
Answer: The input for "Future Ave Weeks to Hold" will be used for the Horizon Years, which are the future years selected by the user. It will apply to the inventory balances after the Beginning Inventory period. If there is no selection for the future years, the default for future years will be the selection indicated for the initial inputs on the Transaction Sheet.
---
Question: What happens if there is no selection for the future years?
Answer: If there is no selection for the future years, the default value for future years will be the selection indicated for the initial inputs on the Transaction Sheet. In other words, the Weeks to Hold value specified for the beginning inventory will be used for all future years if no specific value is provided for the future years. If the Weeks to Hold value is left blank or set to 0, it means that no inventory will be held for use in the future years.
---
Question: What will be used as the default for future years if the "Beginning Inventory" field is left blank?
Answer: If the "Beginning Inventory" field is left blank, the default for future years will be the selection indicated for the initial inputs on the Transaction Sheet.
---
Question: How is the weighted average calculated for Year 1 if the Existing Company is purchasing the Target Company?
Answer: For Year 1, if the Existing Company is purchasing the Target Company, the weighted average for the Weeks to Hold is calculated. This calculation is done by taking into account the Weeks to Hold listed on the Transaction Sheet for the Target Company and the Weeks to Hold listed for the initial input for the Existing Company. The weighted average is calculated based on these two values to determine the average time over which the Inventory will be held for use in Year 1. 
However, it is important to note that for Years after Year 1, the selections in the Ave Weeks to Hold in the Future Input will be used without any weighted average calculation. If there is no selection indicated in the Transaction Sheet for future years, the initial input for the Existing Company will be used.
---
Question: What will be used for future years if there is no selection indicated in the Transaction Sheet?
Answer: If there is no selection indicated in the Transaction Sheet for future years, the default value for future years will be the selection indicated for the initial inputs on the Transaction Sheet. If the initial input is left blank, a value of 0 will be used, indicating that no inventory will be held for use in future years.
---
Question: Where can the "Inventory Weeks to Hold" input be found?
Answer: The "Inventory Weeks to Hold" input can be found in two places: the Inventory Set Up pages for the Transaction Sheet and the Existing Company Inventory Beginning Balances, as well as the Inventory - Future Terms Set-Up Input page.
---
Question: What does "Inventory Future Weeks to Hold" refer to?
Answer: "Inventory Future Weeks to Hold" refers to the average number of weeks that inventory is required to be kept on hand for future periods. It is a parameter that determines the amount of time inventory should be held without being used or sold. This input is used to calculate the inventory levels and planning for future years in the Horizon Period. The value entered should be a whole number and not a fraction of a week.
---
Question: How should the input for "Inventory Future Weeks to Hold" be entered?
Answer: The input for "Inventory Future Weeks to Hold" should be entered as a whole number, representing the average number of weeks that inventory is required to be kept on hand without being used. It should not be entered as a fraction or a portion of a week. This input can be found on the Inventory - Future Terms Set-Up Input page.
