# PBJ-Nurses-Staffing-Analysis
These dataset is based on data submitted by long-term care facilities through the Payroll Based Journal (PBJ) system.

**INTRODUCTION:** 

The Centers for Medicare & Medicaid Services (CMS) provides publicly available datasets, known as the Payroll Based Journal Public Use Files (PBJ PUFs), which offer detailed daily data on nursing home staffing levels and resident census information. These datasets are based on data submitted by long-term care facilities through the Payroll Based Journal (PBJ) system. The PBJ system requires facilities to report accurate and complete direct care staffing details, including those for agency and contract staff, in a standardized, verifiable format. Facilities must submit the paid hours worked by each staff member for every day, along with resident census data sourced from the Minimum Data Set (MDS). This initiative ensures transparency and supports analysis of staffing patterns in nursing homes.

**OBJECTIVES:**

**Understand Staffing Patterns:**
* Identify trends and patterns in staffing levels across various facilities, states, or ownership types.

**Correlate Staffing with Resident Census:**

* Analyze the relationship between daily resident census (patient count) and the staffing hours provided, ensuring that resources align with patient care needs

**Identify Anomalies:**

* Detect outliers or facilities with unusually high or low staffing levels compared to their resident census, which might indicate inefficiencies or potential care gaps.

**Support Transparency and Accountability:**

* Use the findings to help stakeholders understand the accuracy and effectiveness of reported staffing data and align it with CMS standards.

**Guide Resource Allocation:**

* Provide actionable insights for improving staffing distribution to optimize patient care and facility operations.

**Monitor Compliance with Regulations:**

* Check if facilities meet CMS requirements for submitting payroll-based data on direct care staffing and maintaining consistent care standards.

**METHODOLOGY:**

* Data Sourcing – data.cms.gov

* Data cleaning – Power BI: Power BI was used for the loading, cleaning, analysis and visualization. It provides an interactive interface to create reports, dashboards, and visualizations that help
* uncover insights and trends in the data.

**Cleaning:** This involved transforming the data, removing duplicates, replacing Null values, checking for inconsistencies and correcting them, renaming the column headers properly etc.

**Data Analysis:** Using DAX (Data Analysis Expressions) functions and calculations to perform complex data analysis and derive meaningful insights from the data.

**Visualization:** Creating various visualizations, such as bar charts, pie charts, line charts, scatter plots, and tree maps, to represent the data visually and make it easier to understand and 
interpret. 

**Key Performance Indicators Overview:**

1. **Total Medicare Providers:** There are 14,000 Medicare-certified providers (Nurses) actively serving patients across various healthcare facilities.

2. **Total Hours Worked by Nurses:** A total of 821 million hours were contributed by nursing staff, including RNs, LPNs, and CNAs, ensuring consistent patient care.

3. **Total Resident Census (MDS):** The dataset covers 111 million residents, offering insights into occupancy levels across facilities.

4. **Total States Count:** Nursing home operations span 52 states, highlighting nationwide coverage and the scope of data collected.

**INSIGHTS AND RECOMMENDATIONS:**

**1. Sum of Number of Certified Beds by Ownership Type:**

<img width="1108" height="530" alt="image" src="https://github.com/user-attachments/assets/b0b18231-d21a-47ee-a97a-d1f6c50c46bd" />

This chart clearly illustrates the distribution of certified beds across different ownership types, giving stakeholders valuable insights into market dominance, operational focus, and resource 
allocation. 
Now I’ll go further to explain and break it down.

**HOW I ANALYZED THIS DATA**

Using Power BI, I created a clustered bar chart to analyze the sum of Certified Beds by Ownership Type. The ownership types, such as for-profit corporations, limited liability companies, non-
profits, and government entities, were displayed on the vertical axis, while the total number of certified beds was represented on the horizontal axis. 

By aggregating certified beds for each ownership type, I could compare their contributions side by side. Power BI’s chart formatting tools helped me add data labels to clearly display the values 
for each bar. Through this visualization, I identified that for-profit corporations and limited liability companies held the majority of certified beds, whereas government-owned facilities 
contributed significantly fewer beds.

**WHAT I UNCOVERED:**

For-profit corporations and limited liability companies hold the majority share of certified beds, with 578K and 482K beds respectively. We can observe that the high numbers are because it is 
clearly profit oriented. These ownership types play a central role in providing healthcare services across nursing homes. Non-profit corporations account for 223K certified beds, followed by 
church-related and other non-profit entities. These groups prioritize community-focused healthcare. For-profit individual-owned facilities contribute 74K certified beds, while partnerships 
account for 56K beds, showing smaller yet significant involvement. Various government entities (county, state, city, federal) collectively provide fewer certified beds compared to for-profit 
and non-profit organizations, though their focus is typically on underserved areas.

**RECOMMENDATIONS**

To improve collaboration and healthcare service delivery, stakeholders should focus on engaging with for-profit entities, as they dominate the nursing home landscape with the highest share of 
certified beds. They should also support non-profit organizations by providing the necessary resources to strengthen community-focused healthcare services. Government-owned facilities play a 
crucial role in underserved areas, and stakeholders can partner with them to enhance healthcare accessibility. Diversifying resource allocation across various ownership types ensures balanced 
investment in different market segments, while continuously monitoring trends in bed distribution and ownership allows stakeholders to adapt their strategies proactively. These actions 
collectively foster improved patient care and operational efficiency.

**2. Sum of Resident Census MDS And Their Ownership Type:**


<img width="1102" height="530" alt="image" src="https://github.com/user-attachments/assets/ee503c96-b93d-4892-8d70-ba2355f24cba" />

The chart above provides a detailed breakdown of the Resident Census MDS across various ownership types, highlighting the distribution of residents in nursing homes based on ownership categories.
It categorizes ownership into For-Profit, Government, and Non-Profit entities, with subcategories for each type.

**HOW I ANALYZED THIS DATA**

To analyze the data, I imported the dataset into Power BI and created a table chart to effectively visualize the distribution of Resident Census MDS across various ownership types. By using a table
chart, I was able to categorize the data into ownership groups such as For-Profit, Non-Profit, and Government entities. Within these main categories, I further analyzed subcategories, including 
corporations, partnerships, limited liability companies, and state or local government facilities. I calculated the total resident census for each ownership type by aggregating the values in the 
Resident Census MDS column. 

This enabled me to see which ownership types contributed the most to the overall resident count. For example, For-Profit Corporations and Limited Liability Companies had the highest totals, while 
subcategories within government entities had comparatively lower counts.

**WHAT I UNCOVERED:**

For-profit corporations and limited liability companies show the highest sums of Resident Census MDS, indicating their significant role in accommodating residents. Non-profit corporations and church-
related organizations also contribute substantially, while government-owned facilities, such as state and hospital district entities, have varying levels of resident census. This distribution could be influenced by several factors. For-profit organizations often prioritize scalability and profitability, enabling them to operate larger facilities with higher resident capacities. Non-profit entities
focus on community care and service, which drives their substantial contributions. Government facilities, on the other hand, may face funding limitations or operate in underserved areas, which can 
affect their resident numbers.

**RECOMMENDATIONS**

To ensure optimal care and resource allocation, stakeholders and sales team should focus on fostering collaboration between ownership types. For-profit entities can be encouraged to maintain high-
quality care standards despite their scale. Non-profits should receive support to continue their community-focused mission, while government facilities may benefit from consistent funding and stra-
tegic partnerships to enhance their operations. By leveraging the strengths of each ownership type, stakeholders can improve overall care and service delivery for residents.
