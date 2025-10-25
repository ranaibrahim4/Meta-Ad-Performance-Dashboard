# Meta Advertising Analytics Dashboard

A comprehensive data analytics project focused on Meta (Facebook/Instagram) advertising performance analysis and insights generation.

## 📋 Project Overview

This project analyzes Meta advertising data to provide insights into campaign performance, user engagement, and advertising effectiveness across Facebook and Instagram platforms. The analysis includes user demographics, campaign metrics, ad performance, and event tracking.

## 📁 Project Structure

```
├── Raw Data/
│   ├── ad_events.csv      # User interaction events (likes, shares, impressions, etc.)
│   ├── ads.csv            # Ad details and targeting information
│   ├── campaigns.csv      # Campaign metadata and budget information
│   └── users.csv          # User demographics and profile data
├── Images/
│   ├── Facebook_Logo_2023.png
│   ├── Google_Ads_logo.svg.png
│   ├── Instagram_icon.png
│   ├── Threads_(app).png
│   ├── whatsapp.png
│   └── meta_PNG*.png
├── Business Requirements Document.pdf
├── Dashboard Insights.pdf
├── Domain Knowledge Document.pdf
├── Meta AD.pdf
├── Project Explaination in Interview.pdf
└── Screenshot 2025-10-24 161230.png
```

## 📊 Data Schema

### Ad Events (`ad_events.csv`)
- **event_id**: Unique identifier for each event
- **ad_id**: Reference to the specific ad
- **user_id**: User who performed the action
- **timestamp**: When the event occurred
- **day_of_week**: Day of the week
- **time_of_day**: Time period (Morning, Afternoon, Evening, Night)
- **event_type**: Type of interaction (Like, Share, Impression, Click, etc.)

### Ads (`ads.csv`)
- **ad_id**: Unique ad identifier
- **campaign_id**: Reference to the campaign
- **ad_platform**: Platform (Facebook, Instagram)
- **ad_type**: Ad format (Video, Stories, Carousel, Image)
- **target_gender**: Target audience gender
- **target_age_group**: Target age range
- **target_interests**: Interest-based targeting

### Campaigns (`campaigns.csv`)
- **campaign_id**: Unique campaign identifier
- **name**: Campaign name
- **start_date**: Campaign start date
- **end_date**: Campaign end date
- **duration_days**: Campaign duration
- **total_budget**: Total budget allocated

### Users (`users.csv`)
- **user_id**: Unique user identifier
- **user_gender**: User's gender
- **user_age**: User's age
- **age_group**: Age group category
- **country**: User's country
- **location**: User's location
- **interests**: User's interests

## 🎯 Key Features

- **Campaign Performance Analysis**: Track budget utilization, duration, and effectiveness
- **User Engagement Metrics**: Analyze likes, shares, impressions, and clicks
- **Demographic Insights**: Understand user behavior across different age groups and locations
- **Platform Comparison**: Compare performance between Facebook and Instagram
- **Time-based Analysis**: Identify optimal posting times and days
- **Interest Targeting**: Evaluate the effectiveness of interest-based targeting

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook (optional)
- Data analysis libraries (pandas, numpy, matplotlib, seaborn)

### Installation
1. Clone this repository
2. Navigate to the project directory
3. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

### Data Loading
```python
import pandas as pd

# Load the datasets
ad_events = pd.read_csv('Raw Data/ad_events.csv')
ads = pd.read_csv('Raw Data/ads.csv')
campaigns = pd.read_csv('Raw Data/campaigns.csv')
users = pd.read_csv('Raw Data/users.csv')
```

## 📈 Analysis Capabilities

- **Performance Metrics**: CTR, engagement rates, conversion rates
- **Budget Analysis**: ROI, cost per acquisition, budget efficiency
- **Audience Insights**: Demographic breakdowns and behavior patterns
- **Temporal Analysis**: Peak engagement times and seasonal trends
- **Platform Performance**: Cross-platform comparison and optimization

## 📋 Business Requirements

This project addresses key business requirements for Meta advertising optimization:
- Campaign performance tracking and optimization
- User engagement analysis and improvement
- Budget allocation and ROI analysis
- Target audience refinement
- Platform-specific strategy development

## 🔍 Domain Knowledge

The project incorporates domain expertise in:
- Meta advertising ecosystem
- Social media marketing best practices
- Data analytics and visualization
- User behavior analysis
- Campaign optimization strategies

## 📊 Dashboard Insights

The project includes comprehensive dashboard insights covering:
- Real-time performance metrics
- Visual data representations
- Interactive filtering and analysis
- Export capabilities for reporting

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is for educational and analytical purposes.

## 📞 Contact

For questions or collaboration opportunities, please refer to the project documentation or contact the project maintainer.

---

*This project demonstrates advanced data analytics capabilities in the context of Meta advertising, providing actionable insights for marketing optimization and campaign performance improvement.*
