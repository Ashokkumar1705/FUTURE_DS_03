# Marketing Funnel Analysis Project
## Marketing Funnel Analysis – Conversion Drop-off & Channel Performance
### Project Overview
This project analyzes user-level marketing funnel data to identify conversion drop-offs, evaluate channel performance, and recommend actions to improve lead-to-customer conversion. The analysis focuses on understanding where users exit the funnel and whether conversion issues are channel-specific or systemic.

The entire analysis is performed using Python to ensure transparency, reproducibility, and analytical rigor.


###Tools & Technologies
Python
Pandas (data manipulation)
Matplotlib (visualization)
Seaborn (heatmaps)

### Dataset Description

##### The dataset consists of user interaction events across multiple channels:
Email
Google Ads
Organic
Social Media

##### Each row represents a user action mapped to a funnel stage:
Browse → Visit
Add to Cart → Lead
Checkout → Qualified Lead
Purchase → Customer

#### Analysis Workflow

Cleaned and normalized event-level data
Mapped events to funnel stages
Calculated user-level funnel counts
Computed conversion rates at each stage
Performed channel-wise funnel analysis
Visualized insights using Python charts
##### Key Insights

Strong top-funnel engagement across all channels (~69–70%)

Moderate mid-funnel conversion (~48–51%)

Major drop-off at checkout to purchase stage (~27–30%)

Conversion bottleneck is consistent across channels

##### Business Recommendations

Reduce checkout friction by simplifying the payment flow

Improve trust signals during checkout

Retarget checkout abandoners using email and paid ads

Optimize mobile checkout experience
