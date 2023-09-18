# Mpesa Statement Analysis

This is an analysis of an Mpesa statement from May 2022 to May 2023. The statement was generated by Safaricom and you can get yours by dialing *334#
The statement includes my transactions in the 12 months from May 2022. Columns found in the Dataset are:


    1.Receipt No.
    2.Completion Time
    3.Details
    4.Transaction Status
    5.Paid In
    6.Withdrawn
    7.Balance


I converted the statement to the .ods(This is the same as .pdf but i was using Libre Office instead of Excel because of my OS) file aand removed the password feature where a password input was needed before acessing the file.

I then converted the .ods file to a dataframe using pandas, followed by pivoting the dataframe to keep the relevant columns. After pivoting the columns that i kept were:


    1.Completion Time
    2.Details
    3.Paid In
    4.Withdrawn


## **I was then able to analyse the data to come up with the following insights:**

![Alt text](<Dashboard 1 (1).png>)


 _The Total Received Amount was**Ksh 468,474.82**_

 _The Total Amount Spent was **Ksh 468,381.71**_

 _The Highest Amount Spent was **Ksh 20790.0** to **Cuea Via Citi**_

 _The Highest Amount Received was **Ksh 21046.0** via **CHIME INC**_



 _Out of the **Ksh 100,005.00** sent via Send Money **Ksh 1,722.00** was charged as Transaction Fees_

 _Out of the **Ksh 146,451.00** transacted via the Lipa na Mpesa option **Ksh 772.00** was charged as Transaction Fees_

 _Out of the **Ksh 8,700.00** withdrawn **Ksh 390** was charged as Withdrawal Fees_