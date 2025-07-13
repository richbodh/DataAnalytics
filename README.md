# DataAnalytics
Task 1: Enquiry and Transaction Counts
a. As a first step, the output schema(enq_txn_count) is created.
b. Using Subqueries and UNION ALL merged and inserted the data in the output schema.
c. With the select statement, result is displayed.

Task 2: Enquiry Conversion Mapping
a. As a first step, the output schema (enq_cnv_map) is created.
b. Using CTE and JOIN conditions, converted enquiry details are stored in a temp table named conv_enq.
c. Then using Subquery and JOIN conditions, details of unconverted enquiries are selected and stored both, converted and unconverted enquiries details in the output schema using UNION ALL.
d. In the select statement of output schema, transaction IDs are converted into an array and result is displayed.
