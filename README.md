focusing on:

Player scouting (xG, passes, defensive actions)

Match analysis report

Outcome prediction

Computer vision tracking

### Folder Structure:
```
soccer-analytics/
├── data/
│   ├── raw/
│   ├── processed/
│   └── scraped/  ← FBref or Understat scraped data
├── notebooks/
│   ├── 01_exploration.ipynb
│   ├── 02_scouter.ipynb
│   ├── 03_outcome_model.ipynb
│   └── 04_sentiment.ipynb
├── dashboards/
│   └── player_scouting_dashboard.twbx
├── src/
│   ├── scraping/
│   ├── etl/
│   ├── modeling/
│   └── tracking/
├── match_reports/
│   └── ucl_final_report.pdf
├── video_tracking/
│   └── video_clip_tracking.mp4
├── blog_drafts/
│   └── xg_analysis_blog.md
├── README.md
└── requirements.txt

```
