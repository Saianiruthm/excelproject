# Introduction
Welcome to the Laptop Dynamics Project!

Dive into the intricate world of laptops as we unravel the nuances hidden within the data. Our dataset, a treasure trove of laptop specifications, prices, and key attributes, is the cornerstone of this exploration. Through meticulous analysis, we aim to uncover the trends and patterns shaping the laptop market.

With attributes ranging from screen size and resolution to CPU and GPU specifics, our dataset encapsulates the essence of various laptop models, offering a comprehensive view of the landscape. Join us in deciphering the correlations between specifications and prices, unearthing insights that illuminate the evolving preferences of consumers in this tech-driven era.

## Dataset Structure & Data Cleansing
Our initial dataset, primarily structured around key attributes such as:
- Company
- TypeName
- Inches
- ScreenResolution
- Cpu
- Ram
- Memory
- Gpu
- OpSys
- Weight
- Price

Lays the foundation for our analysis. However, to ensure the integrity of our analysis, we embarked on a meticulous data cleansing journey.

### Handling Null Values
Null values can often skew analyses, compromising the reliability of results. Through rigorous data processing, we addressed any null values within the dataset. Columns were carefully examined, and appropriate strategies were employed to handle missing data.

### Evolving Column Structure in the Final File
In refining our dataset, we identified opportunities to enhance the structure further. The final file structure encompasses additional attributes beyond the initial set, including:
- IPS Panel
- Display Type
- Touch Screen
- Resolution
- CPU Company
- CPU Type
- CPU Model
- Clock Speed(GHz)
- I-Memory(GB)
- I-Storage Type
- II-Memory(GB)
- II-Storage Type
- GPU Company
- GPU Model
- OpSys
- Weight (in kg)
- Price
- Range

## Presentation of Data
1. **LaptopData Sheet**: Cleaned Dataset in PowerPivot Table
2. **Pivot1 Sheet**: Count Tables for Key Attributes
3. **Charts1 Sheet**: Visual Representations of Pivot1 Tables
4. **Pivot2 Sheet**: Company-Specific Count Tables
5. **Charts2 Sheet**: Visual Representation of Pivot2 Tables
6. **Detailed Display Analysis**

## Data Analytics
### Questions Explored
- Which Company Has the Highest Average Laptop Price?
- How Does RAM Size Correlate with Laptop Prices?
- Impact of CPU Type on Laptop Prices
- Distribution of Operating Systems Among Laptops
- Visualizing Price Distribution Across Different Laptop Types

### Insights and Visualizations
- **Company-wise Price Analysis**: Visualizations and pivot tables showcased the distribution of laptop prices across different companies.
- **Correlation Between RAM and Price**: Observations revealed a positive correlation between RAM size and laptop prices.
- **CPU and GPU Impact on Prices**: Clear depictions of how different CPU and GPU types affected laptop prices were derived.

### Excel Functions Utilized
Our analysis was empowered by a diverse set of Excel functions, including VLOOKUP, COUNTIF, SUMIF, and Pivot Tables.

## GitHub Repository
Our analysis and findings are documented within our [GitHub repository](GitHub Repository Link).

### Contents of the Repository
- LaptopData.csv: Our raw dataset
- LaptopData.xlsx: Final curated dataset
- Medium Article: A detailed Medium article encapsulating our analysis

## Contribution and Collaboration
We welcome contributions, suggestions, and collaborations from the community.

### Explore the Repository
Head over to the [GitHub Repository](https://github.com/Saianiruthm/excelproject.git) to delve deeper into our analysis.

## Conclusion
Our analysis unearthed intricate details within the laptop market. Factors like RAM size, CPU, and GPU types strongly influence pricing strategies and consumer preferences. However, while our analysis provided valuable insights, there are limitations due to the scope of available data.

### Final Thoughts
Our endeavor to dissect laptop data underscores the evolving dynamics of consumer preferences and technological advancements.

This analysis serves as a stepping stone for deeper dives into understanding consumer behaviors and industry trends.
