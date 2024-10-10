# Data Mining
Market Basket Analysis

Part I: Research Question
- The following research question will be applied for this data mining report: Which prescriptions are often prescribed together?
  
- The goal of this data mining report is to discover key associations of patient’s prescriptions. 
 
Part II: Market Basket Justification

Market basket analysis works by first re-expressing transactional data, such as patient’s prescriptions. This process is completed with a transaction encoder so that each item becomes its own column. For example, each prescribed medication becomes its own column. Then the aproiri algorithm is applied. The aproiri algorithm reviews the data to identify frequencies of each item and identify pairs of items that frequently occur together. After collecting association information, support and confidence metrics are calculated to measure the reliability and importance of acquired associations (Kadlaskar). Then association rules amongst items are derived based on the frequency of items, support, and confidence. After the association rules are generated, the lift metric is calculated. The lift metric indicates how likely the association rule applies (Kadlaskar). The expected outcome is paired prescriptions that are often prescribed together based on the generated association rules. 

Part III: Data Summary and Implications

The support values show how frequently the pair of prescriptions occurred. The greater the support value, the higher the frequency of occurrence of paired items. The association table shows that Abilify co-prescribed with carvedilol has the highest value of support which means it occurs most frequently. The lift values in the association table are all greater than 1 which indicates that the association rule generated is likely. The top two lift values indicate that the co-prescription of abilify and carvedilol, along with abilify and diazepam, are likely to occur. Confidence measures the likelihood of the association rule generated (Kausar). Based on the association table, the co-prescription of abilify and carvedilol has the highest confidence value which means that association rule is reliable.

Overall, the results indicate that abilify is the most frequently prescribed medication and is often co-prescribed with carvedilol. If abilify is not co-prescribed with carvedilol then diazepam prescription is likely. If abilify is not co-prescribed with diazepam or carvedilol, then amphetamine salt combo xr prescription is likely, but the frequency of this occurring is not as high as the previous rules mentioned. 


Based on results, the most frequent co-prescription is abilify and carvedilol, and it is recommended that the side effects and long-term effects of combining both medications are reviewed, and that each patient’s health record analyzed to ensure the reduction of negative medication interactions and worsening health conditions.  There is evidence that this medication combination can significantly lower blood pressure (“Abilify and Carvedilol Interactions”). It would be ideal to monitor blood pressure for all patients that are prescribed abilify and carvedilol. 


Part IV: Sources

Raschka, Sebastian. “Association Rules - Mlxtend.” Rasbt.github.io, rasbt.github.io/mlxtend/user_guide/frequent_patterns/association_rules/. Accessed 25 Mar. 2024.

---. “TransactionEncoder - Mlxtend.” Rasbt.github.io, rasbt.github.io/mlxtend/user_guide/preprocessing/TransactionEncoder/. Accessed 25 Mar. 2024.
 


“Abilify and Carvedilol Interactions.” Drugs.com, www.drugs.com/drug-interactions/abilify-with-carvedilol-233-109-531-0.html#:~:text=Interactions%20between%20your%20drugs&text=ARIPiprazole%20and%20carvedilol%20may%20have. Accessed 26 Mar. 2024.

Kadlaskar, Amruta. “Market Basket Analysis | Guide on Market Basket Analysis.” Analytics Vidhya, 2 Oct. 2021, www.analyticsvidhya.com/blog/2021/10/a-comprehensive-guide-on-market-basket-analysis/. Accessed 25 Mar. 2024.

Kausar, Rifat Al. “Market Basket Analysis Using MLxtend Library in Python.” Medium, 27 Sept. 2023, medium.com/@rifatalkausar/market-basket-analysis-using-mlxtend-library-in-python-7e56bd41a569. Accessed 26 Mar. 2024.

“Market Basket Analysis.” HUA’S Analysis, 1 Sept. 2015, sarahtianhua.wordpress.com/portfolio/market-basket-analysis/#:~:text=The%20underlying%20assumption%20in%20market. Accessed 25 Mar. 2024.


