# Dataset: Bank Marketing

Citation Request:
  This dataset is public available for research. The details are described in [Moro et al., 2011]. 
  Please include this citation if you plan to use this database:

  *[Moro et al., 2011] S. Moro, R. Laureano and P. Cortez. **Using Data Mining for Bank Direct Marketing: An Application of the CRISP-DM Methodology.***

  *In P. Novais et al. (Eds.), **Proceedings of the European Simulation and Modelling Conference - ESM'2011**, pp. 117-121, Guimarães, Portugal, October, 2011. EUROSIS.*

  Available at:
  
   [http://hdl.handle.net/1822/14838](http://hdl.handle.net/1822/14838) <br />
   [http://www3.dsi.uminho.pt/pcortez/bib/2011-esm-1.txt](http://www3.dsi.uminho.pt/pcortez/bib/2011-esm-1.txt)

**1. Title:** Bank Marketing

**2. Sources**
   Created by: Paulo Cortez (Univ. Minho) and Sérgio Moro (ISCTE-IUL) @ 2012
   
**3. Past Usage:**

  The full dataset was described and analyzed in:

  *S. Moro, R. Laureano and P. Cortez. **Using Data Mining for Bank Direct Marketing: An Application of the CRISP-DM Methodology.***

  *In P. Novais et al. (Eds.), **Proceedings of the European Simulation and Modelling Conference - ESM'2011**, pp. 117-121, Guimarães, Portugal, October, 2011. EUROSIS.*

**4. Relevant Information:**

   The data is related with direct marketing campaigns of a Portuguese banking institution. 
   The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, 
   in order to access if the product (bank term deposit) would be (or not) subscribed. 

   There are two datasets: 
      1) bank-full.csv with all examples, ordered by date (from May 2008 to November 2010).
      2) bank.csv with 10% of the examples (4521), randomly selected from bank-full.csv.
   The smallest dataset is provided to test more computationally demanding machine learning algorithms (e.g. SVM).

   The classification goal is to predict if the client will subscribe a term deposit (variable y).

**5. Number of Instances:** 45211 for bank-full.csv (4521 for bank.csv)

**6. Number of Attributes:** 16 + output attribute.

**7. Attribute information:**

    For more information, read [Moro et al., 2011].

   ## Input variables:
   ***
   ### bank client data:
   **1 - age:** (numeric)<br />
   **2 - job:** type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student",
                                       "blue-collar","self-employed","retired","technician","services")<br /> 
   **3 - marital :** marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)<br />
   **4 - education:** (categorical: "unknown","secondary","primary","tertiary")<br />
   **5 - default:** has credit in default? (binary: "yes","no")<br />
   **6 - balance:** average yearly balance, in euros (numeric)<br />
   **7 - housing:** has housing loan? (binary: "yes","no")<br ;>
   **8 - loan:** has personal loan? (binary: "yes","no")<br />

   ## related with the last contact of the current campaign:
   ***
   
   **9 - contact:** contact communication type (categorical: "unknown","telephone","cellular")<br />
  **10 - day:** last contact day of the month (numeric)<br />
  **11 - month:** last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")<br />
  **12 - duration:** last contact duration, in seconds (numeric) 
  ## other attributes:
  **13 - campaign:** number of contacts performed during this campaign and for this client(numeric, includes last contact)<br />
  **14 - pdays:** number of days that passed by after the client was last contacted from aprevious     campaign (numeric, -1 means client was not previously contacted)<br ;>
  **15 - previous:** number of contacts performed before this campaign and for this client(numeric)<br />
  **16 - poutcome:** outcome of the previous marketing campaign (categorical: "unknown","other""failure","success")<br />
  ## Output variable (desired target):    
  ***
  **17 - y**: has the client subscribed a term deposit? (binary: "yes","no")<br />


**8.Missing Attribute Values:** None
