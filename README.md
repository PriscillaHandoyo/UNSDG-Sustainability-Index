# UNSDG AI Sustainability Index
Making the World a Better Place with Data and Artificial Intelligence

## Project Overview
This project is all about using computers and smart programs (called machine learning) to help us understand how well different countries are doing in making the world a better place. We look at big goals from the United Nations called Sustainable Development Goals (SDGs) – like ending poverty, protecting the environment, and giving everyone access to good education and healthcare. We take important numbers (called indicators) from each country and use them to create a single score that shows how sustainable that country is. This helps us compare countries, see who’s doing well, and find out where we can improve.

## Project Goals
1. **Combine many important facts** (like education and health) into one score for each country.
2. **Group countries** that have similar scores.
3. **Predict the future** – will things get better or worse in the next few years?
4. **Give advice** to leaders to help them improve their countries.

## Key Components
1. **What We Look At (Indicators)**
We gather facts and numbers from trusted websites like the United Nations and World Bank. These are some of the things we look at:
- **Education**: Are kids going to school? Can people read and write?
- **Health**: Are babies healthy? How long do people live?
- **Environment**: How much pollution is there? Are countries using clean energy?
- **Money and Poverty**: How rich is a country? How many people are poor?
- **Gender Equality**: Are girls and women getting the same chances as boys and men?

2. **Cleaning and Preparing the Data**
Before we use the data, we: 
- Fill in missing information (or remove it if it’s not helpful).
- Make sure all the numbers are in the same format.
- Check that the data matches the right country and year.

3. **Creating the Sustainability Score**
We can make the score in two ways:
- **Weighted Formula**: We give more importance to some indicators and add them up.
- **Smart Compression**: We let the computer find the most important patterns using a technique like PCA (Principal Component Analysis).

4. **Grouping Countries (Clustering)**
We use machine learning to group countries that are similar. For example:
- **High Performers**: Doing great in most areas.
- **At Risk**: Struggling with big problems.
- **Emerging Regions**: Improving, but still have work to do.
We use computer techniques like **K-Means** or **DBSCAN** to do this.

5. **Predicting the Future (Optional)**
If we have data from past years, we can train the computer to **predict** what might happen in the future. Will education improve? Will pollution go down? This helps us prepare for what’s coming.

6. **Giving Smart Advice**
Once we understand which countries are doing well and which ones need help, we can give **ideas and advice** to leaders. We also find out **which indicators matter the most** – is health more important than income? Should we focus on education first?

## Tools We Use
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, XGBoost
- **Visuals**: Charts with Matplotlib, Seaborn, or Plotly
- **Dashboard**: Streamlit or Tableau (to make cool interactive websites)
- **Where We Put Our Work**: GitHub and Streamlit Cloud
  
## What We’ll Achieve
- A score for each country based on sustainability.
- Groups of countries with similar scores.
- Predictions for how each country might do in the future.
- Smart advice to help the world become a better, fairer, and cleaner place.
