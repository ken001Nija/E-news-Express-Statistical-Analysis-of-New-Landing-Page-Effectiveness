# 📊 E-news Express: Statistical Analysis of New Landing Page Effectiveness

## 📝 Business Context

E-news Express, an online news portal, aims to expand its subscriber base. The company has redesigned its landing page with a new outline and more relevant content to improve user engagement and conversion rates. To evaluate the effectiveness of this new landing page, an A/B test was conducted comparing the new page (treatment group) against the old page (control group).

## 🎯 Objectives

The main objectives of this analysis are:

1. **Evaluate User Engagement**: Determine if users spend more time on the new landing page than on the old landing page.
2. **Conversion Rate Analysis**: Assess whether the conversion rate (proportion of visitors who subscribe) is higher for the new landing page.
3. **Language Preference Impact**: Investigate if the converted status (whether a user subscribes or not) depends on the preferred language of the user.
4. **Time Spent Across Languages**: Analyze whether the time spent on the new page varies among different language users.

## 📁 Data Overview

The dataset contains 100 user records and includes the following fields:
- `user_id`: Unique identifier for each user.
- `group`: Indicates if the user is in the control group (old page) or treatment group (new page).
- `landing_page`: Specifies the version of the landing page (old or new).
- `time_spent_on_the_page`: The time (in minutes) the user spent on the landing page.
- `converted`: Whether the user subscribed to the news portal (`yes` or `no`).
- `language_preferred`: The language chosen by the user to view the landing page.

## 📊 Analysis and Findings

### 1. **User Engagement: Time Spent on the Page** ⏱️

**Hypothesis**: Users spend more time on the new landing page than on the old landing page.

- **Statistical Summary**:
  - **Old Landing Page**: Mean time spent = 4.53 minutes, Std = 2.58 minutes.
  - **New Landing Page**: Mean time spent = 6.22 minutes, Std = 1.82 minutes.

- **Test Used**: One-tailed t-test at a 5% significance level.
- **Result**: The p-value obtained was 0.0001, which is less than the significance level of 0.05. Thus, we reject the null hypothesis and conclude that users spend significantly more time on the new landing page.

### 2. **Conversion Rate Analysis** 📈

**Hypothesis**: The conversion rate for the new landing page is higher than for the old page.

- **Conversion Rate**:
  - **Old Landing Page**: Conversion rate = 38%.
  - **New Landing Page**: Conversion rate = 70%.

- **Test Used**: Chi-square test for independence.
- **Result**: The chi-square test yielded a p-value of 0.0001, which is less than 0.05. Hence, we reject the null hypothesis, indicating a significant increase in the conversion rate for the new landing page.

### 3. **Impact of Language Preference on Conversion** 🌐

**Hypothesis**: The conversion rate is independent of the preferred language.

- **Test Used**: Chi-square test for independence.
- **Result**: The p-value obtained was 0.43, greater than the significance level of 0.05. Therefore, we fail to reject the null hypothesis, suggesting that the conversion rate does not significantly depend on the preferred language.

### 4. **Time Spent Across Different Languages** 🕒

**Hypothesis**: Time spent on the new page is the same across different language users.

- **Test Used**: One-way ANOVA.
- **Result**: The ANOVA test yielded a p-value of 0.43, which is greater than 0.05. Thus, we fail to reject the null hypothesis, indicating no significant difference in time spent on the new page across different language users.

## 📌 Conclusion

The analysis concludes that the new landing page is more effective in engaging users and improving conversion rates. However, language preference does not significantly impact conversion rates or time spent on the new landing page.

## 📈 Recommendations

- **Optimize for English-speaking Users**: As English users are more engaged, consider further optimizing content for this demographic.
- **Tailor Strategies for French and Spanish Users**: Conduct targeted research to understand these users better and enhance their engagement.
- **Continuous Monitoring and Testing**: Regularly analyze user engagement data to refine the landing page and maximize its effectiveness.


Feel free to modify or add any additional insights based on further analysis or specific business needs!
