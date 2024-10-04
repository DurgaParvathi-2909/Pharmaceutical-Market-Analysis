# Pharmaceutical Market Analysis: Bangladesh Generic Medicine Market
𝐏𝐫𝐨𝐣𝐞𝐜𝐭 𝐎𝐯𝐞𝐫𝐯𝐢𝐞𝐰:
This project provides an in-depth analysis of the Bangladesh Generic Medicine Market using a comprehensive dataset comprising information on medicine brands, generics, manufacturers, drug classes, and dosage forms. 

The primary goal is to uncover key trends, pricing structures, competition dynamics, and market segments using Power BI for data visualization. This analysis will be beneficial for pharmaceutical companies, healthcare professionals, policymakers, and researchers to make data-driven decisions and improve access to affordable medicines.

𝗗𝗮𝘁𝗮𝘀𝗲𝘁𝘀 𝗨𝘀𝗲𝗱
The project leverages six datasets to deliver a comprehensive analysis:

𝗺𝗲𝗱𝗶𝗰𝗶𝗻𝗲.𝗰𝘀𝘃:
Contains data on medicine brands, dosages, prices, and associated generic names.

𝗺𝗮𝗻𝘂𝗳𝗮𝗰𝘁𝘂𝗿𝗲𝗿.𝗰𝘀𝘃:
Provides details on pharmaceutical manufacturers, including their unique IDs, locations, and production capacities.
𝗶𝗻𝗱𝗶𝗰𝗮𝘁𝗶𝗼𝗻.𝗰𝘀𝘃:

Captures data on medical indications associated with different medicines, helping analyze the therapeutic applications.

𝗴𝗲𝗻𝗲𝗿𝗶𝗰.𝗰𝘀𝘃:
Includes the generic names of drugs, dosage information, and market presence.

𝗱𝗿𝘂𝗴_𝗰𝗹𝗮𝘀𝘀.𝗰𝘀𝘃:
Lists the drug classifications, therapeutic categories, and chemical classes for a broad view of the market composition.

𝗱𝗼𝘀𝗮𝗴𝗲_𝗳𝗼𝗿𝗺.𝗰𝘀𝘃:
Defines various dosage forms like tablets, injections, syrups, and their corresponding formulations.

𝐌𝐞𝐭𝐡𝐨𝐝𝐨𝐥𝐨𝐠𝐲

𝟭. 𝗗𝗮𝘁𝗮 𝗖𝗹𝗲𝗮𝗻𝗶𝗻𝗴
Addressed missing values, removed duplicate records, and ensured consistent formatting.
Standardized units for dosages (e.g., mg, mL, IU) to make comparisons easier across different medicines.

𝟮. 𝗗𝗮𝘁𝗮 𝗠𝗼𝗱𝗲𝗹𝗶𝗻𝗴
Established relationships between the tables by creating key links such as manufacturer_id between medicine.csv and manufacturer.csv, and generic drug names between medicine.csv and generic.csv.
Built a star schema model to facilitate efficient querying and reporting in Power BI.

𝟯. 𝗘𝘅𝗽𝗹𝗼𝗿𝗮𝘁𝗼𝗿𝘆 𝗗𝗮𝘁𝗮 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀 (𝗘𝗗𝗔)
Analyzed pricing patterns by manufacturer, drug class, and dosage form.
Explored the distribution of medicines across different therapeutic areas and identified top manufacturers and drug categories.

𝟰. 𝗩𝗶𝘀𝘂𝗮𝗹𝗶𝘇𝗮𝘁𝗶𝗼𝗻𝘀 𝗮𝗻𝗱 𝗗𝗮𝘀𝗵𝗯𝗼𝗮𝗿𝗱
Developed an interactive Power BI dashboard showcasing market overviews, top players, competition levels, pricing trends, and regional disparities in drug availability.

𝐊𝐞𝐲 𝐈𝐧𝐬𝐢𝐠𝐡𝐭𝐬

𝗠𝗮𝗿𝗸𝗲𝘁 𝗖𝗼𝗺𝗽𝗼𝘀𝗶𝘁𝗶𝗼𝗻:
The dataset reveals that there are 21,714 medicine brands, 1,711 generics, 240 manufacturers, 453 drug classes, and 113 dosage forms available in the market.
Cardiovascular drugs and diabetes treatments dominate the market due to the prevalence of chronic diseases in the country.

𝗟𝗲𝗮𝗱𝗶𝗻𝗴 𝗣𝗹𝗮𝘆𝗲𝗿𝘀:
Incept Pharmaceuticals Ltd. emerges as the top manufacturer with the highest number of drugs in the market, followed by Square Pharmaceuticals Ltd. and Beximco Pharmaceuticals Ltd..
Cefixime trihydrate is the most frequently produced generic, with widespread use in antibiotics.

𝗣𝗿𝗶𝗰𝗶𝗻𝗴 𝗧𝗿𝗲𝗻𝗱𝘀:
Significant pricing differences exist between locally manufactured generics and imported ones, with local drugs being more affordable.
Highly competitive categories like anti-hypertensive medicines (387 brands) show a general reduction in average prices due to market competition.

𝗡𝗶𝗰𝗵𝗲 𝗠𝗮𝗿𝗸𝗲𝘁𝘀:
Herbal medicines constitute only 1.62% of the total market share, indicating limited presence but potential growth opportunities in alternative medicines.

𝗔𝗻𝘁𝗶𝗺𝗮𝗹𝗮𝗿𝗶𝗮𝗹 𝗗𝗿𝘂𝗴 𝗠𝗮𝗿𝗸𝗲𝘁:
The analysis reveals 53 brands of antimalarial drugs produced by 23 manufacturers. Mefloquine stands out with only one competitor, suggesting limited market competition for this drug.

𝗥𝗲𝗴𝗶𝗼𝗻𝗮𝗹 𝗗𝗶𝘀𝗽𝗮𝗿𝗶𝘁𝗶𝗲𝘀:
There are significant variations in drug availability and pricing across different regions, with rural areas facing challenges such as limited supply and higher costs.

𝐂𝐡𝐚𝐥𝐥𝐞𝐧𝐠𝐞𝐬

𝗗𝗮𝘁𝗮 𝗖𝗹𝗲𝗮𝗻𝗶𝗻𝗴: 
Handling inconsistent dosage units (e.g., mg, mL, IU) and standardizing them for accurate analysis.

𝗖𝗼𝗺𝗽𝗹𝗲𝘅 𝗥𝗲𝗹𝗮𝘁𝗶𝗼𝗻𝘀𝗵𝗶𝗽𝘀:
 Mapping complex relationships between drug classes, generics, and manufacturers proved challenging due to missing values and incomplete data in some records.

𝗥𝗲𝗴𝗶𝗼𝗻𝗮𝗹 𝗗𝗮𝘁𝗮 𝗚𝗮𝗽𝘀: 
The dataset lacked granular regional data for rural markets, limiting the scope of the analysis in some areas.

𝐂𝐨𝐧𝐜𝐥𝐮𝐬𝐢𝐨𝐧𝐬

𝗦𝘁𝗿𝗮𝘁𝗲𝗴𝗶𝗰 𝗙𝗼𝗰𝘂𝘀 𝗼𝗻 𝗖𝗵𝗿𝗼𝗻𝗶𝗰 𝗜𝗹𝗹𝗻𝗲𝘀𝘀:
With chronic diseases like cardiovascular and diabetes being the primary focus of the generic medicine market, manufacturers should invest in expanding their offerings in these areas to meet growing demand.

𝗖𝗼𝗺𝗽𝗲𝘁𝗶𝘁𝗶𝘃𝗲𝗻𝗲𝘀𝘀 𝗮𝗻𝗱 𝗣𝗿𝗶𝗰𝗶𝗻𝗴:
The highly competitive nature of some drug segments, such as anti-hypertensives, leads to price reductions, making these medicines more affordable. This could be a model for other therapeutic areas with less competition.

𝗢𝗽𝗽𝗼𝗿𝘁𝘂𝗻𝗶𝘁𝗶𝗲𝘀 𝗳𝗼𝗿 𝗚𝗿𝗼𝘄𝘁𝗵 𝗶𝗻 𝗛𝗲𝗿𝗯𝗮𝗹 𝗠𝗲𝗱𝗶𝗰𝗶𝗻𝗲𝘀:
The herbal medicine market remains underdeveloped. Companies could tap into this niche by investing in alternative treatments and addressing the growing consumer interest in natural products.

𝗘𝘅𝗽𝗮𝗻𝗱𝗶𝗻𝗴 𝗔𝗰𝗰𝗲𝘀𝘀 𝗶𝗻 𝗥𝘂𝗿𝗮𝗹 𝗔𝗿𝗲𝗮𝘀:
Pharmaceutical companies should explore opportunities to improve drug availability in rural regions, where logistics and supply chain challenges lead to limited access and higher prices.

𝗠𝗮𝗿𝗸𝗲𝘁 𝗣𝗼𝘁𝗲𝗻𝘁𝗶𝗮𝗹 𝗳𝗼𝗿 𝗡𝗶𝗰𝗵𝗲 𝗗𝗿𝘂𝗴𝘀:
Drugs like Mefloquine, with minimal competition, present opportunities for manufacturers to expand their product lines in niche therapeutic categories.

# Snapshot of Pharmaceutical Market Analysis (Power BI Desktop)
![Pharmaceutical Market Analysis](https://github.com/user-attachments/assets/93d6227e-2308-4d36-8ef4-7633f60a3836)

 
 
