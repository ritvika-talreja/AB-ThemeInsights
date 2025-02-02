# AB-ThemeInsights
A/B Testing (also known as split testing) is a statistical method used to compare two versions of a product, feature, or process to determine which one performs better. It helps in making data-driven decisions by evaluating changes in user behavior, conversion rates, or other key metrics.

## Overview 
This project analyzes the effectiveness of light versus dark themes on a website through comprehensive A/B testing. The analysis examines various metrics including click-through rates, conversion rates, bounce rates, scroll depth, and session duration to determine if there are significant differences in user behavior between the two themes.

## How A/B Testing Works
(i) Hypothesis Creation:
You start with a hypothesis, like "Changing the website's theme from Light to Dark will improve conversion rates."

(ii) Splitting the Audience:
The audience is randomly divided into two groups:

Group A (Control Group): Exposed to the current version (e.g., Light Theme).

Group B (Variant Group): Exposed to the new version (e.g., Dark Theme).

(iii) Running the Test:
Both groups interact with their respective versions under similar conditions.

(iv) Measuring Metrics:
Metrics such as Click-Through Rate (CTR), Conversion Rate, Bounce Rate, or Session Duration are tracked.

(v) Statistical Analysis:
Statistical tests like the z-test (for proportions) or t-test (for means) are used to determine if observed differences are statistically significant or due to random chance.

(vi) Decision Making:
Based on the analysis:
If the variant performs significantly better, it's adopted.
If there’s no significant difference, the original version may be retained.

##  Statistical Tests
(i) Purchase Conversion A/B Test
*  Two-sample proportion test comparing purchase rates
*  Results: Light Theme (53.09%) vs Dark Theme (50.39%)
*  Not statistically significant (p-value: 0.394)

(ii) Session Duration A/B Test
*  Two-sample t-test comparing average session duration
*  Results: Light Theme (930.83s) vs Dark Theme (919.48s)
*  Not statistically significant (p-value: 0.724)

## Key Findings

* Light theme showed slightly better performance across metrics but differences were not statistically significant
* Purchase conversion rate was 2.7 percentage points higher in light theme
* Session duration was approximately 11.35 seconds longer in light theme
* Neither theme showed a clear statistical advantage over the other
