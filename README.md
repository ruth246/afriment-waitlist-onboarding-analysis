Afriment Waitlist & Onboarding Analysis
## 1. Project Overview

This project analyzes Afriment waitlist and onboarding data across multiple learner cohorts to understand participant demographics, geographic distribution, acquisition channels, and enrollment patterns.
The analysis focuses on identifying patterns in the waitlist, understanding how participants discovered Afriment, and generating insights that can support recruitment, onboarding, and learner growth strategies.

## 2. Project Objectives

The main objectives of this analysis are to:
* Analyze waitlist and onboarding patterns across learner cohorts.
* Understand the demographic characteristics of participants.
* Examine geographic distribution across countries and cities.
* Evaluate the effectiveness of referral and acquisition channels.
* Identify patterns in learner participation and enrollment.
* Examine relationships between participant characteristics and referral sources.
* Generate data-driven insights to support recruitment, onboarding, and learner growth.

## 3. Dataset Overview

The dataset contains waitlist and onboarding records from **Afriment learner cohorts 12–19**, covering eight cohorts.
The data contains information used to analyze participant demographics, location, referral sources, and cohort participation patterns.

### Key Data Fields

* **Cohort** — identifies the learner cohort.
* **Gender** — participant gender.
* **Country** — participant country.
* **City** — participant location.
* **Referral Source** — channel through which participants discovered Afriment.
* **Waitlist / Onboarding Information** — information used to examine participation and enrollment patterns.


## 4. Data Cleaning & Preparation

The dataset was cleaned and prepared before analysis to improve data quality and ensure reliable results.

### Data Cleaning Steps

* Removed unnecessary spaces and standardized text entries.
* Cleaned and standardized phone number formats, including local and international formats.
* Identified and handled missing values in relevant fields.
* Checked for duplicate records.
* Standardized cohort, gender, country, city, and referral-source categories.
* Reviewed inconsistent or incomplete entries to improve consistency across the dataset.
* Validated the cleaned data before proceeding with analysis and visualization.

## 5. Analysis & Visualization

The cleaned dataset was analyzed to identify patterns and trends in learner participation, demographics, geographic distribution, and acquisition channels.

### Key Analysis Areas

* Analyzed waitlist participation across cohorts 12–19.
* Examined gender distribution and participation patterns.
* Analyzed participant distribution by country and city.
* Evaluated referral sources to understand how participants discovered Afriment.
* Compared referral-source patterns across gender groups.
* Identified the most prominent acquisition channels.
* Examined cohort-level patterns and changes in participation.

### Visualization

Interactive dashboards were developed using **Google Looker Studio** to present key findings through charts, filters, and summary metrics.

## 6. Statistical Analysis

Statistical techniques were applied to investigate relationships within the dataset, including:

* **Correlation analysis** to examine relationships between relevant numerical variables.
* **Chi-square test of independence** to assess the relationship between gender and referral source.

The Chi-square analysis produced a **χ² value of 12.36, with 5 degrees of freedom and a p-value of 0.030**, indicating a statistically significant association between gender and referral source at the 5% significance level.

## 7. Key Findings & Insights

* **Nigeria accounted for approximately 97%** of participants, with Ghana and Kenya representing smaller shares.
* **Female participants were significantly more represented** than male participants in the waitlist.
* **LinkedIn was a major referral source**, followed by referrals from friends.
* Referral-source patterns varied by gender, with the Chi-square analysis indicating a statistically significant association between gender and referral source.
* Participation patterns varied across cohorts, providing insights into learner recruitment and onboarding trends.

## 8. Recommendations

* **Partner with male-dominated tech schools and hubs** and introduce more male-oriented technical courses to improve male participation and gender balance.
* **Organize hackathons and ambassador programs** to increase visibility, engagement, and learner acquisition.
* **Leverage alumni testimonials and success stories** across digital channels to build credibility and attract new learners.
* **Strengthen high-performing referral channels**, particularly LinkedIn and referral-based channels, to support continued membership growth.

## 9. Tools Used

* **Excel** — data cleaning, transformation, analysis, and exploratory analysis.
* **MySQL** — data querying and analysis.
* **Google Looker Studio** — interactive dashboards and data visualization.
* **Statistical Analysis** — correlation analysis and hypothesis testing.

## 10. Dashboard & Project Deliverables

### Dashboard

An interactive **Google Looker Studio dashboard** was developed to present key waitlist and onboarding insights, including:

* Cohort participation
* Gender distribution
* Geographic distribution
* Referral-source performance
* Key demographic patterns

### Project Deliverables

* Cleaned dataset
* SQL analysis
* Excel analysis
* Statistical analysis
* Interactive Looker Studio dashboard
* Data-driven recommendations
