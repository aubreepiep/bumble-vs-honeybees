# Bumble and the Bees
[Presentation Link](https://www.canva.com/design/DAGZBd_bxAA/UGptKi8T_ykjJVto8Awy7A/view?utm_content=DAGZBd_bxAA&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h8cede17887)  
[Dashboard Link](https://app.powerbi.com/links/w61vwZIYml?ctid=101da587-1843-4f52-8b8a-17b069c66d33&pbi_source=linkShare&bookmarkGuid=b8e85c3d-1eee-4f42-88c9-14742f2cfdd6)

## Executive Summary:
The project uses the corporate financial lens to compare the productivity of honey bees to the company, Bumble. It draws on data from USDA honey production information as well as Bumble financial statements. The audience will consider the potential benefits and risks of becoming a stakeholder in each entity. More broadly, the project will show how we can creatively recontextualize natural systems (like honey production) in corporate terms to better understand (and marvel at) their impact.

## Motivation:
My goal is to build and demonstrate my fluency in business reporting metrics while also exploring something outside the typical business assignment. This is also a good opportunity to celebrate how busy and important bees are even if they don't have the glamour of a high-growth startup!

## Data Questions:

### How would the annual performance reports of honey bees compare to the annual reports released by Bumble? What are the relative strengths and weaknesses of each entity and what opportunities and risks should potential stakeholders be aware of? 
#### Key Metrics (annually and 3 year average)
-Revenue  
-Gross Profit Margin  
-Profit Margin  
#### Other Questions
-How would queen bees be compensated if they were paid on similar scale to bumble CEOs?  
-How does each entity diversify revenue streams? What percentage of total revenue does each revenue stream make up?  
-What other vulnerabilities may impact each entity?  

## Analysis and Presenation methods
#### Primary Data Sources
[Bumble Inc. Annual Report 2023](https://s202.q4cdn.com/372973788/files/doc_financials/2023/ar/Bumble-Inc-Annual-Report-2023.pdf)  
[Bumble Inc. Proxy Statement 2024](https://s202.q4cdn.com/372973788/files/doc_financials/2024/sr/Bumble-Inc-Proxy-Statement-2024.pdf)  
[Bumble Inc. Quarterly Results 2022-2024](https://ir.bumble.com/financials/quarterly-results/default.aspx)  
[USDA  National Agricultural Statistics Service (NASS) Honey Reports 3/15/24](https://downloads.usda.library.cornell.edu/usda-esmis/files/hd76s004z/hm50wd54j/fq979h127/hony0324.pdf)  
[USDA National Agricultural Statistics Service (NASS) Honey Reports 3/17/23](https://downloads.usda.library.cornell.edu/usda-esmis/files/hd76s004z/jq086x851/qn59rh469/hony0323.pdf)  

## Analysis Methods and Assumptions
I attempted to do a side-by-side business analysis of Bumble Inc performance and bee producivity. While there are many obvious differences between a tech company and bees, I did my best to align metrics into their most comparable forms.   
This was most pronounced in my calculation of gross profit and profit margin. In order to compare Bumble and Bees on even footing, I only accounted for costs that could be incurred by both entities. For example, I did not subtract Bumble's marketing costs from their gross profit because there is no similar way for bees to market their services. As a result, my reporing of Bumble's profit and profit margins will be different than the numbers reported in their financial reports.

## Technologies Used
All data was originally in PDF form. It was parsed using **excel's** pdf data import function and then imported into **Python** as a CSV. I used the Python **pandas** library for general analysis, the **locale** libary to clean commas from numeric values, and the **matplot** and **seaborn** libraries for data visualization.
My presentation was created in **Canva** and my accompanying dashboard was created in **Power BI**.