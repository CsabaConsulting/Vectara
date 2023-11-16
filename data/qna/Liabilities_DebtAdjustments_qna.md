Question: What are the two methods for making extra payments or draws on Debt?
Answer: The two methods for making extra payments or draws on Debt are the Cash Flow Control page and the Adjusting Journal Entry (AJE) process.
---
Question: How are payments and draws entered for Debt transactions?
Answer: Payments and draws for Debt transactions can be entered using two methods: the Cash Flow Control page and the Adjusting Journal Entry (AJE) process. 
For both methods, a positive number is entered for payments, and a negative number is entered for draws. 
1. Cash Flow Control:
   - This method is used as a cash flow and debt management tool.
   - Payments made directly to the debt on the Cash Flow Control page are in addition to any regularly scheduled payments on the debt.
   - This provision allows surplus cash to be applied to pay down debt or, if applicable, drawing new debt to supplement cash.
2. Adjusting Journal Entry (AJE) Process:
   - This method allows for more specific adjustments to debt transactions.
   - Payments and draws can be made directly to the Transaction Sheet loan or to individual loans in the Individually Scheduled Loan Categories.
   - For Transaction Sheet Loans, payments and draws can be made directly to the loan. If a draw is made during the original term of the loan, regular payments will stay the same, and the draw balance will remain for the remaining term with any unpaid balance becoming a balloon payment at the end of the term.
   - For Individually Scheduled Loans, payments and draws can also be made directly to the Transaction Sheet loan. If a draw is made during the original term of the loan, regular payments will stay the same, and the draw balance will remain for the remaining term with any unpaid balance becoming a balloon payment at the end of the term. However, for certain loan types, draws are not allowed before the loan is scheduled to begin or after the loan is paid off.
   - AJEs can be used to make adjustments to individual loans within the debt category.
It is important to note that additional payments are first applied to accrued interest and then to the principal balance, except for Seller Debt, which has a specific payment allocation discussed separately.
---
Question: How are additional payments applied to Debt?
Answer: Additional payments on Debt are applied in a specific order. First, they are applied to accrued interest, and then to the principal balance. However, this allocation method does not apply to Seller Debt. The allocation of payments to Seller Debt is as follows: outstanding interest on the Non-Current Pay Seller Note, principal on the Non-Current Pay Seller Note, outstanding interest on the Earn Out Seller Note, principal on the Earn Out Seller Note (if not amortized), interest on the Current Pay Seller Note, and finally, principal on the Current Pay Seller Note. It is important to note that this allocation method applies to additional payments made directly to the debt on the Cash Flow Control page or through the Adjusting Journal Entry (AJE) process.
---
Question: Can draws be made on the Individual Scheduled Loans through the Cash Flow Input page?
Answer: No, draws cannot be made on the Individual Scheduled Loans through the Cash Flow Input page. Disbursements for Individual Scheduled Loans can be scheduled in subsequent years using the Individually Scheduled Item Input form by setting the disbursement as a separate Debt Item. Alternatively, an Adjusting Journal Entry (AJE) disbursement can be made specifically to an Individually Scheduled Item through the AJE Input page.
---
Question: How are payments and draws allocated for Transaction Sheet Loans?
Answer: For Transaction Sheet Loans, payments will first reduce the loan balance on the Transaction Sheet. If there are multiple Individual Scheduled Loans, the payment will then be allocated to each of these loans in proportion to their individual balances at the time of payment. 
Draws on Transaction Sheet Loans, if made during the original term of the loan, will reset the original loan term. However, if the draw is made after the term expires, the draw amount will be paid back the following year.
---
Question: What happens if a draw is made after the term expires for Transaction Sheet Loans?
Answer: If a draw is made after the term expires for Transaction Sheet Loans, the draw will be paid back the next year.
---
Question: How are payments and draws allocated for Individually Scheduled Loans?
Answer: For Individually Scheduled Loans, payments are first applied to the Transaction Sheet loan. After that, they are allocated to each of the Individual Scheduled Loans in proportion to their individual loan balances at the time of payment. This means that the loans with higher balances will receive a larger portion of the payment.
On the other hand, draws should not be made on the Individual Scheduled Loans through the Cash Flow Input page. Instead, disbursements may be scheduled in subsequent years in the Individually Scheduled Item Input form by setting the disbursement as a separate Debt Item. An Adjusting Journal Entry (AJE) disbursement may also be made specifically to an Individually Scheduled Item through the AJE Input page.
It's important to note that if a draw is made during the original term of the loan, the regular payments will stay the same and the draw balance will remain for the remaining term with the unpaid balance becoming a balloon payment at the end of the term. However, if the draw is made after the term expires, for certain loan types, the draw amount will be interest only and remain until paid off with another AJE. For other loan payment types, draws are not allowed before the loan is scheduled to begin or on or after the loan is paid off.
In summary, payments for Individually Scheduled Loans are allocated proportionally based on the individual loan balances, while draws should be made through the Individually Scheduled Item Input form or the AJE Input page.
---
Question: What happens if a draw is made after the term expires for loan types 0 and 3?
Answer: If a draw is made after the term expires for loan types 0 and 3 (Interest Only), the draw amount will be interest only and will remain until paid off with another Adjusting Journal Entry (AJE). This means that the draw will not be applied to the principal balance of the loan.
---
Question: Can draws be made on Other Transaction Debt?
Answer: Draws can be made on Other Transaction Debt. However, it is important to note that any draw made on this category of loans will only be applied to the first loan in the category. When making a draw, a negative number should be entered. If the draw is made during the term of the first original loan in the category, it will fall under the remaining term of the original loan with the same stated interest rate and payment terms. If the draw is made after the term expires, the draw amount will create a loan balance until adjusted again with either a Cash Flow Sheet adjustment or another Adjusting Journal Entry (AJE). Interest will be paid on the balance annually until it is paid off with either another Cash Flow Sheet adjustment or AJE.
---
Question: How are payments and draws allocated for Other Transaction Debt?
Answer: For Other Transaction Debt, payments are allocated to each loan in the category in proportion to the outstanding balance of each loan at the time of payment. The payments are first applied to any accrued interest and then to the principal balance in proportion to each loan's balance to the total.
On the other hand, draws can only be made to the first loan in the category. If a draw is made during the term of the first original loan, it will fall under the remaining term of the original loan with the same stated interest rate and payment terms. If the regular payments and any extra payments do not pay off the loan at the end of the term, the remaining balance will be paid off in a balloon payment.
It is important to note that if a draw or adjusting journal entry (AJE) is made for a period after the loan term has expired and the original loan has been paid off, the amount of the draw or AJE will create a loan balance until adjusted again with either a cash flow sheet adjustment or another AJE. Interest will be paid on the balance annually until it is paid off with either another cash flow sheet adjustment or AJE.
Lastly, it should be mentioned that a cash flow adjustment or AJE that creates a negative loan amount will result in an error.
---
Question: Can draws be made on Other Current Debt?
Answer: Draws can be made on Other Current Debt through the Cash Flow Input page. However, it is important to note that when a Cash Flow Control Draw is made to Other Current Debt, there is no identification to one of the Individually Scheduled Debt Items. As a result, the Cash Flow Draw will be immediately paid off in the same year and will have no effect. Draws on Other Current Debt will only have an impact on the Transaction Sheet loan for other Individually Scheduled Items, as they all have Transaction Sheet portions.
---
Question: How can the Credit Line feature be activated for Other Current Debt?
Answer: The Credit Line feature for Other Current Debt can be activated by entering a Credit Limit amount in Step 6 of the *ThruThink* software. This Credit Limit amount will apply to the portion of the beginning Other Current Debt that is not a part of the Individually Scheduled Other Current Debt. Once the Credit Limit is set, the General Other Current Debt amount will roll into a Credit Line facility with weekly automatic draws and payments to the cash account. This feature allows for more flexibility in managing and tracking the Other Current Debt.
---
Question: What are Individually Scheduled Other Debt?
Answer: Individually Scheduled Other Debt refers to individual short-term liabilities that have specific funding dates and are paid off 12 months later. These debts can have different interest rates or no interest at all. They are separate from the general Other Current Debt category and are tracked individually. The Individually Scheduled Other Debt items can be renewed each year, extending their payment schedule for another 12 months. Payments or draws on these debts can be made through the Adjusting Journal Entry (AJE) process, allowing for specific adjustments to be made to each debt item.
---
Question: How can the Individually Scheduled Debt portion of Other Current Debt be paid down?
Answer: The Individually Scheduled Debt portion of Other Current Debt can be paid down through the Cash Flow Control page or by making Adjusting Journal Entries (AJEs). 
On the Cash Flow Control page, any surplus cash can be applied to pay down the Individually Scheduled Debt portion of Other Current Debt. This payment will be in addition to any regularly scheduled payments on this debt as inputted by the user when setting up the debt. 
Alternatively, AJEs can be made to increase or decrease the Individually Scheduled Debt portion. These AJEs can be used to make specific adjustments to the debt balance. 
It is important to note that any adjustments or payments made to the Individually Scheduled Debt portion should be managed with subsequent payments through the Cash Flow Control page or AJEs, as the regular payments only manage the original loan balances.
---
Question: How can adjustments be made to the Non Interest Bearing Portion of Other Current Debt?
Answer: Adjustments to the Non Interest Bearing Portion of Other Current Debt can be made through an Adjusting Journal Entry (AJE) process. In Step 7 of the software, you can use an AJE to increase or decrease the balance of the Non Interest Bearing Portion for each year of the Horizon. This allows you to manually adjust the amount in this category to reflect any changes or corrections needed.
---
Question: How can Other Debt be created?
Answer: Other Debt can be created by using the Individual Scheduled Item Debt Set up and selecting Other Debt as a category. This allows for the creation of a separate debt item specifically categorized as Other Debt. Draws on Other Debt are not available through the Cash Flow Input page. When a Cash Flow Control Draw is made to Other Debt, there is no identification to one of the Individually Scheduled Debt Items, and the Cash Flow Draw will be immediately paid off in the same year. A Cash Flow Draw to Other Debt will have no effect. Disbursements for Other Debt may be scheduled in subsequent years in the Individually Scheduled Item Input form by setting the disbursement as a separate Debt Item. An Adjusting Journal Entry (AJE) disbursement may also be made specifically to an Individually Scheduled Item through the AJE Input page. A draw on Other Debt will fall under the remaining term of the loan with the same stated Interest Rate and payment terms. If a draw is made and the regular payments plus any extra payments do not pay off the loan at the end of the term, the balance will be paid off at the end of the stated term in a balloon payment. If individual activity (Payment or Draw) is needed for each loan in the Other Debt category separately, an AJE may be made to each specific loan.
---
Question: Can draws be made on Other Debt through the Cash Flow Input page?
Answer: No, draws cannot be made on Other Debt through the Cash Flow Input page. Other Debt is an Individually Scheduled Item and does not have a Transaction Sheet portion. Therefore, when a Cash Flow Control Draw is made to Other Debt, there is no identification to one of the Individually Scheduled Debt Items, and the Cash Flow Draw will be immediately paid off in the same year. A Cash Flow Draw to Other Debt will have no effect.
---
Question: How are payments and draws allocated for Seller Debt?
Answer: For Seller Debt, excess cash pay down is allocated in a specific order. First, it is applied to outstanding interest on the Non-Current Pay Seller Note. Then, it is applied to the principal on the Non-Current Pay Seller Note. Next, it is applied to the outstanding interest of the Earn Out Seller Note. If the Earn Out Seller Note is not amortized, the excess cash pay down is applied to the principal of the Earn Out Seller Note. Finally, any remaining excess cash pay down is applied to the interest of the Current Pay Seller Note, followed by the principal of the Current Pay Seller Note.
