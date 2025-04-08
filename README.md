# Netflix Data Analysis: Mental Health & Cultural Diversity

![Netflix Logo](https://upload.wikimedia.org/wikipedia/commons/7/77/Netflix_avatar.png)

An exploratory analysis of Netflix titles (2010-2023) to evaluate representation of mental health themes and cultural diversity.

**Current Status**: Baseline analysis completed | Next steps outlined below

## 📊 Project Overview
- **Dataset**: 8,000+ Netflix titles (columns: `show_id`, `type`, `title`, `country`, `release_year`, `duration`, `listed_in`, `description`, etc.)
- **Goal**: Identify gaps in mental health representation and cultural diversity
- **Tools Used**: Python (Pandas, Seaborn), Jupyter Notebook

## 🔍 Current Findings
### 1. Basic Visualizations
- Histograms for numerical data (release years, durations)
- Bar charts for categorical analysis (countries, genres)
- Correlation heatmap between key variables
- Scatter plot: `release_year` vs. `duration`

### 2. Preliminary Insights
```python
# Sample query from current work
sns.scatterplot(x='release_year', y='duration', data=df)
