# Data source

Download `cookie_cats.csv` from [Mobile Games: A/B Testing on Kaggle](https://www.kaggle.com/datasets/yufengsui/mobile-games-ab-testing).

The Kaggle publisher credits the DataCamp project *Mobile Games A/B Testing with Cookie Cats*. The original experiment and data collection were not conducted by the author of this analysis.

Put the CSV in `data/raw/cookie_cats.csv`. Raw data is excluded from the distributable archive and Git tracking. Kaggle lists the dataset license as **Unknown**; consult the publisher's terms before redistributing source data.

| Column | Meaning used in this analysis |
|---|---|
| userid | Player identifier |
| version | Assigned gate variant: gate_30 or gate_40 |
| sum_gamerounds | Number of game rounds recorded in the dataset |
| retention_1 | Recorded return on day 1 after installation |
| retention_7 | Recorded return on day 7 after installation |

Day-7 retention means returning on day 7, not returning at any point during the first week. A False value does not mean a player never returned on another day.
