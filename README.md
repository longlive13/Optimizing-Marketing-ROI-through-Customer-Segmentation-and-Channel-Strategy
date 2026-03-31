# Optimizing-Marketing-ROI-through-Customer-Segmentation-and-Channel-Strategy

##  Objectives
This project analyzes marketing performance across customer segments and channels, 
and derives actionable strategies through data-driven insights and what-if simulations.

#2. Data & Method

#3. Exploratory Analysis
##3.1. Optimizing Marketing ROI through Customer Segmentation and Channel Strategy
<img width="640" height="480" alt="channel_roi_vs_conversion" src="https://github.com/user-attachments/assets/f2853ee2-ef83-4006-90c2-bc716db312d6" />
**Result**
- Email shows the highest ROI with relatively low conversion rate  
- SMS has the highest conversion rate with moderate ROI  
- Phone has high conversion rate but very low ROI  

**Interpretation**
- Email is a cost-efficient channel, while SMS is more effective for conversion  
- Phone generates conversions but at a disproportionately high cost  

**Implication**
- Relying solely on conversion rate can lead to misleading decisions  
- Channel performance should be evaluated using both ROI and conversion rate  

##3.2. ROI by Campaign Frequency
<img width="640" height="480" alt="roi_by_campaign_frequency" src="https://github.com/user-attachments/assets/81dbb503-7434-4661-a4bc-49f4837f44e5" />
**Result**
- ROI is highest at 1–2 contacts  
- ROI drops significantly after 3–4 contacts  
- ROI becomes negative at 5+ contacts  

**Interpretation**
- Increasing contact frequency leads to diminishing returns  
- Excessive contact results in cost inefficiency  

**Implication**
- There is an optimal contact threshold  
- Limiting campaign frequency can improve overall marketing efficiency


##3.3 Segment x Channel
<img width="640" height="480" alt="roi_by_segment_channel" src="https://github.com/user-attachments/assets/e0c01dac-d5c7-4835-a7be-9548879db7db" />
**Result**
- Top-performing combinations are mostly Email-based  
- High ROI segments include Young–Mid, Young–High, and Senior–Mid/High  
- Some SMS combinations also show strong performance  

**Interpretation**
- Performance is concentrated in specific segment–channel combinations  
- Not all customer groups respond equally to the same channel  

**Implication**
- Targeted marketing strategies outperform uniform approaches  
- Budget allocation should focus on high-performing segment–channel pairs

  
##3.4 Negative ROI Segments
<img width="640" height="480" alt="negative_roi_segments" src="https://github.com/user-attachments/assets/c394045c-95b9-4bd7-b0c8-608b198fc9d2" />
**Result**
- Top-performing combinations are mostly Email-based  
- High ROI segments include Young–Mid, Young–High, and Senior–Mid/High  
- Some SMS combinations also show strong performance  

**Interpretation**
- Performance is concentrated in specific segment–channel combinations  
- Not all customer groups respond equally to the same channel  

**Implication**
- Targeted marketing strategies outperform uniform approaches  
- Budget allocation should focus on high-performing segment–channel pairs


##3.5. Channel Cost Efficiency
<img width="640" height="480" alt="channel_cost_efficiency" src="https://github.com/user-attachments/assets/06f1312e-3aa4-478f-ba94-7d15c28f00c9" />
**Result**
- Email has the highest ROI  
- SMS shows moderate ROI  
- Phone has the lowest ROI  

**Interpretation**
- Email is the most cost-efficient channel  
- Phone is the least efficient despite reasonable conversion  

**Implication**
- Budget should be reallocated toward Email and efficient SMS use  
- Phone channel requires optimization or reduction

  
##  Key Takeaways
- High ROI does not necessarily mean high conversion (ROI illusion exists)  
- Increasing contact frequency reduces efficiency beyond a threshold  
- Marketing performance is highly dependent on segment–channel alignment  
- Certain channel–segment combinations generate consistent losses  
- Budget reallocation and targeting are critical for ROI optimization  

## What-if Simulation Results
<img width="640" height="480" alt="whatifscenario" src="https://github.com/user-attachments/assets/abe47e12-0123-4d40-9977-a5f02bc678b5" />

|index|scenario|total\_cost|total\_revenue|ROI|ROI\_change|
|---|---|---|---|---|---|
|0|Current|304498\.5|264450\.0|0\.868477184616673|0\.0|
|1|Remove Negative ROI|27394\.9|263800\.0|9\.629529583973659|8\.761052399356986|
|2|Campaign Cap \(\<=3\)|141637\.3|229000\.0|1\.616805742555104|0\.7483285579384309|
|3|Remove Phone|74203\.49999999999|166550\.0|2\.244503291623711|1\.3760261070070379|
|4|Top 20% Focus|3180\.0|18900\.0|5\.943396226415095|5\.074919041798422|

### 🔍 Interpretation

The simulation results reveal that removing inefficient segments and channels has a significant impact on overall marketing performance.

Eliminating negative ROI segments resulted in the most dramatic improvement, increasing ROI from 0.87 to 9.63, indicating that loss-making activities were the primary factor reducing profitability.

Limiting campaign frequency to three contacts improved ROI to 1.62, confirming that excessive customer contact leads to diminishing returns.

Removing the Phone channel further increased ROI to 2.24, suggesting that it is a cost-inefficient channel despite its relatively high conversion rate.

Focusing only on the top 20% of segment–channel combinations yielded a high ROI of 5.94, demonstrating the effectiveness of targeted marketing strategies.

### 💡 Implications

- Loss-making segments significantly dilute overall ROI and should be prioritized for removal  
- Excessive campaign exposure reduces efficiency and should be controlled  
- Cost-inefficient channels (e.g., Phone) require optimization or budget reduction  
- Targeted investment in high-performing segment–channel combinations leads to substantial ROI improvement  
