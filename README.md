# Gun-Related Mortality Analysis

Contributors: Lillian Pulaski, Gabriella Coleman, Melanie Nguyen, Renzo Guevarra

May 2025

A comprehensive data analysis project examining gun-related deaths in the United States (2012-2014) to identify trends, at-risk populations, and inform policy recommendations for violence prevention.

## Project Overview

This is an academic project where our team acted as data analysts contracted by the National Safety Council (NSC) to analyze gun-related mortality data and provide evidence-based recommendations for reducing gun violence. We combined technical data analysis skills with a social justice lens to uncover patterns in gun deaths and propose targeted interventions.

## Dataset

The analysis uses data compiled by FiveThirtyEight from multiple authoritative sources:

- **CDC Multiple Cause of Death Database** - Primary mortality data
- **FBI Police Shootings Data** - Law enforcement involved incidents  
- **Mother Jones Mass Shooting Database** - Mass shooting incidents
- **University of Maryland Global Terrorism Database** - Terrorism-related incidents

### Data Structure

The dataset contains the following categorical variables:
- `year`, `month` - Temporal information (2012-2014)
- `sex`, `age`, `race` - Demographic information
- `education` - Education level of deceased
- `intent` - Type of incident (homicide, suicide, legal intervention, accidental)
- `place` - Location where incident occurred
- `police` - Boolean indicator for police involvement
- `hispanic` - Hispanic origin codes per CDC classification

## Research Questions

Our analysis addresses four key research questions:

1. **Temporal Trends**: What are the trends in gun-related deaths over time (2012–2014), and how do they vary by intent?

2. **Demographic Analysis**: How do gun-related deaths differ across demographic groups (age, sex, race, education)?

3. **Education Correlation**: What is the relationship between education level and gun-related deaths?

4. **Predictive Analysis**: Can we predict the likelihood of a gun-related death being classified as suicide vs. homicide based on demographic characteristics?

## Key Findings

### Seasonal Patterns
- **Suicides**: Peak during spring/summer months (March-May), with notable decline during winter
- **Homicides**: Increase during warmer months (June-August), with December spikes during holiday season

### At-Risk Demographics
- **Middle-aged white males**: Highest suicide rates
- **Young Black men (18-34)**: Disproportionately affected by homicides, particularly those with high school education or less
- **Native American/Alaska Native populations**: Third most significant predictor for suicide risk despite small population percentage

## Technologies Used

- **Python** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **Matplotlib/Seaborn** - Data visualization (line graphs, heatmaps, bar charts)
- **Scikit-learn** - Logistic regression for predictive modeling

## Policy Recommendations

### Mental Health Initiatives
- Target mental health services for middle-aged white males
- Implement nationwide campaigns to destigmatize mental health help-seeking
- Increase mental health awareness during warmer months

### Gun Control Measures
- Advocate for stricter background checks and waiting periods
- Implement continuous mental health assessments for gun owners
- Focus on preventing impulsive purchases by at-risk individuals

### Community-Based Programs
- Educational initiatives and mentorship for young Black men
- Community events during warmer months as violence alternatives
- Workplace mental health programs during high-stress periods

### Targeted Research
- Dedicated studies on Native American/Alaska Native communities
- Geographic analysis to identify high-risk locations
- Longitudinal studies extending beyond 2012-2014 timeframe

## Future Research Directions

1. **Geographic Analysis**: Incorporate state/city-level data for targeted interventions
2. **Extended Timeline**: Include data from 2004-2024 for comprehensive trend analysis
3. **Native American Focus**: Dedicated research on overlooked indigenous communities
4. **Intersectional Analysis**: Examine how multiple demographic factors interact

## Data Sources & References

- [CDC Hispanic Origin Code List](https://www.cdc.gov/nchs/data/dvs/Appendix_D_Accessible_Hispanic_Origin_Code_List_Update_2011.pdf)
- [CDC Suicide Statistics](https://blogs.cdc.gov/nchs/2014/01/10/1121/)
- [CDC Tribal Suicide Prevention](https://www.cdc.gov/suicide/programs/tribal.html)
